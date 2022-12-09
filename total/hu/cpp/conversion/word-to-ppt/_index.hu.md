---
title: A WORD konvertálása PPT-re C++ segítségével
description: Exportáljon WORD-t PPT-be C++-alkalmazásaiban Microsoft Word of PowerPoint használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: PPT
otherformats: POT PPTX PPTM POTX PPSX PPS POWERPOINT PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a WORD konvertálásához PPT-vé" h2="WORD exportálása PPT-be a C++-alkalmazásokon belül a Microsoft Word&reg; vagy PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) olyan hatékony fájlautomatizálási API-kból áll, amelyek lehetővé teszik a WORD- PPT-konverzió automatizálását, miközben két API-t használ. Töltse be a WORD-t az [Aspose.Words for C++] segítségével (https://products.aspose.com/words/cpp/), konvertálja HTML-vé, majd töltse be a HTML-t a PowerPoint manipulációs C++ API-n keresztül [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) új prezentáció létrehozásához és PPT-ként mentéséhez. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORD konvertálás PPT-be C++-on" %}}
1. Nyissa meg a WORD-fájlt a [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument) osztályhivatkozás használatával
2. Alakítsa át a WORD-t HTML-vé a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_stdbasicostream_saveoptions) tagfüggvény használatával
3. Inicializáljon egy új [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objektumot
4. Adjon hozzá egy AutoShape-ot a diához, és adja hozzá az AddTextFrame-et
5. Töltse be a HTML tartalmat, és írja be a bemutató fájlba
6. Mentse a dokumentumot PPT formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) módszerrel, és állítsa be az Ppt-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORD file with an instance of Wordument
Wordument wordument = new Wordument("template.wordx");
System::SharedPtr<Wordument> word = System::MakeObject<Wordument>(u"sourceFile.wordx");
// save the wordument in HTML file format
word->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Töltsön be jelszóval védett WORD-dokumentumot C++-on keresztül" %}}
A dokumentumok konvertálásán kívül az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API rengeteg dokumentumkezelési funkciót tesz lehetővé a C++ fejlesztői számára. Ha a Microsoft Word WORD fájlformátuma jelszóval védett, akkor is megnyithatja az API használatával. A titkosított dokumentum betöltéséhez használhat egy speciális konstruktor túlterhelést, amely elfogad egy [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objektumot. Ez az objektum tartalmazza a Jelszó tulajdonságot, amely a jelszó karakterláncot adja meg.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordument, the password is passed to the wordument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordPassword");
// load the wordument from the local file system by filename:
SharedPtr<Wordument> word = MakeObject<Wordument>(u"Encrypted.wordx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Megjegyzések hozzáadása az PPT-dokumentumhoz C++-on keresztül" %}}
Miközben a WORD-t PPT-ként menti, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) segítségével további funkciókat is hozzáadhat PPT-dokumentumához. Például megjegyzéseket fűzhet a prezentációjához. A bemutató dia megjegyzései egy adott szerzőhöz vannak társítva. A Prezentáció osztály az ICommentAuthorCollection gyűjteményét tartalmazza azon szerzők gyűjteményében, amelyek a diák megjegyzéseinek hozzáadásáért felelősek. Minden szerzőhöz van egy megjegyzésgyűjtemény az ICommentCollectionben.
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-pot/" name="WORDX Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-pptx/" name="WORDX Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-pptm/" name="WORDX Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-potx/" name="WORDX Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-ppsx/" name="WORDX Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-pps/" name="WORDX Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-powerpoint/" name="WORDX Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-ppsm/" name="WORDX Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-potm/" name="WORDX Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/wordx-to-ppt/" name="WORDX Nak nek PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}