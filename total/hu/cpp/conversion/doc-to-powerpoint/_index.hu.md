---
title: A DOC konvertálása POWERPOINT-re C++ segítségével vagy ingyenes online konverterrel
description: Exportáljon DOC-t POWERPOINT-be C++-alkalmazásaiban Microsoft Word of PowerPoint használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes POT-CSV online konvertert.

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: PPTX
otherformats: PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a DOC konvertálásához POWERPOINT-vé vagy Online App" h2="DOC exportálása POWERPOINT-be a C++-alkalmazásokon belül a Microsoft Word&reg; vagy PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) olyan hatékony fájlautomatizálási API-kból áll, amelyek lehetővé teszik a DOC- POWERPOINT-konverzió automatizálását, miközben két API-t használ. Töltse be a DOC-t az [Aspose.Words for C++] segítségével (https://products.aspose.com/words/cpp/), konvertálja HTML-vé, majd töltse be a HTML-t a PowerPoint manipulációs C++ API-n keresztül [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) új prezentáció létrehozásához és POWERPOINT-ként mentéséhez. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOC konvertálás POWERPOINT-be C++-on" %}}
1. Nyissa meg a DOC-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozás használatával
2. Alakítsa át a DOC-t HTML-vé a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions) tagfüggvény használatával
3. Inicializáljon egy új [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objektumot
4. Adjon hozzá egy AutoShape-ot a diához, és adja hozzá az AddTextFrame-et
5. Töltse be a HTML tartalmat, és írja be a bemutató fájlba
6. Mentse a dokumentumot POWERPOINT formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) módszerrel, és állítsa be az Powerpoint-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOC file with an instance of Document
Document document = new Document("template.doc");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.doc");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter DOC-hez POWERPOINT-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Töltsön be jelszóval védett DOC-dokumentumot C++-on keresztül" %}}
A dokumentumok konvertálásán kívül az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API rengeteg dokumentumkezelési funkciót tesz lehetővé a C++ fejlesztői számára. Ha a Microsoft Word DOC fájlformátuma jelszóval védett, akkor is megnyithatja az API használatával. A titkosított dokumentum betöltéséhez használhat egy speciális konstruktor túlterhelést, amely elfogad egy [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objektumot. Ez az objektum tartalmazza a Jelszó tulajdonságot, amely a jelszó karakterláncot adja meg.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.doc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Megjegyzések hozzáadása az POWERPOINT-dokumentumhoz C++-on keresztül" %}}
Miközben a DOC-t POWERPOINT-ként menti, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) segítségével további funkciókat is hozzáadhat POWERPOINT-dokumentumához. Például megjegyzéseket fűzhet a prezentációjához. A bemutató dia megjegyzései egy adott szerzőhöz vannak társítva. A Prezentáció osztály az ICommentAuthorCollection gyűjteményét tartalmazza azon szerzők gyűjteményében, amelyek a diák megjegyzéseinek hozzáadásáért felelősek. Minden szerzőhöz van egy megjegyzésgyűjtemény az ICommentCollectionben.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-ppsx/" name="DOC Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-pptx/" name="DOC Nak nek PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-ppt/" name="DOC Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-pot/" name="DOC Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-potx/" name="DOC Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-potm/" name="DOC Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-pptm/" name="DOC Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-ppsm/" name="DOC Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-pps/" name="DOC Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-powerpoint/" name="DOC Nak nek POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}