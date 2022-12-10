---
title: A WORDML konvertálása PPSM-re C++ segítségével
description: Exportáljon WORDML-t PPSM-be C++-alkalmazásaiban Microsoft Word of PowerPoint használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: PPSM
otherformats: PPTX POWERPOINT PPT POT PPTM POTM PPSX PPS POTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a WORDML konvertálásához PPSM-vé" h2="WORDML exportálása PPSM-be a C++-alkalmazásokon belül a Microsoft Word&reg; vagy PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) olyan hatékony fájlautomatizálási API-kból áll, amelyek lehetővé teszik a WORDML- PPSM-konverzió automatizálását, miközben két API-t használ. Töltse be a WORDML-t az [Aspose.Words for C++] segítségével (https://products.aspose.com/words/cpp/), konvertálja HTML-vé, majd töltse be a HTML-t a PowerPoint manipulációs C++ API-n keresztül [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) új prezentáció létrehozásához és PPSM-ként mentéséhez. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDML konvertálás PPSM-be C++-on" %}}
1. Nyissa meg a WORDML-fájlt a [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) osztályhivatkozás használatával
2. Alakítsa át a WORDML-t HTML-vé a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions) tagfüggvény használatával
3. Inicializáljon egy új [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objektumot
4. Adjon hozzá egy AutoShape-ot a diához, és adja hozzá az AddTextFrame-et
5. Töltse be a HTML tartalmat, és írja be a bemutató fájlba
6. Mentse a dokumentumot PPSM formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) módszerrel, és állítsa be az Ppsm-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Töltsön be jelszóval védett WORDML-dokumentumot C++-on keresztül" %}}
A dokumentumok konvertálásán kívül az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API rengeteg dokumentumkezelési funkciót tesz lehetővé a C++ fejlesztői számára. Ha a Microsoft Word WORDML fájlformátuma jelszóval védett, akkor is megnyithatja az API használatával. A titkosított dokumentum betöltéséhez használhat egy speciális konstruktor túlterhelést, amely elfogad egy [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objektumot. Ez az objektum tartalmazza a Jelszó tulajdonságot, amely a jelszó karakterláncot adja meg.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Megjegyzések hozzáadása az PPSM-dokumentumhoz C++-on keresztül" %}}
Miközben a WORDML-t PPSM-ként menti, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) segítségével további funkciókat is hozzáadhat PPSM-dokumentumához. Például megjegyzéseket fűzhet a prezentációjához. A bemutató dia megjegyzései egy adott szerzőhöz vannak társítva. A Prezentáció osztály az ICommentAuthorCollection gyűjteményét tartalmazza azon szerzők gyűjteményében, amelyek a diák megjegyzéseinek hozzáadásáért felelősek. Minden szerzőhöz van egy megjegyzésgyűjtemény az ICommentCollectionben.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-pptx/" name="WORDML Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-powerpoint/" name="WORDML Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-ppt/" name="WORDML Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-pot/" name="WORDML Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-pptm/" name="WORDML Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-potm/" name="WORDML Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-ppsx/" name="WORDML Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-pps/" name="WORDML Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-potx/" name="WORDML Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordml-to-ppsm/" name="WORDML Nak nek PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}