---
title: Converteer DOCX naar PPSX via C++
description: Exporteer DOCX naar PPSX in uw C++-toepassingen zonder Microsoft Word of PowerPoint te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: PPSX
otherformats: POT PPT POTX PPTX PPS PPSM POWERPOINT PPTM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om DOCX naar PPSX te converteren" h2="Exporteer DOCX naar PPSX binnen uw C++-toepassingen zonder Microsoft Word&reg; of PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bestaat uit krachtige API's voor bestandsautomatisering waarmee de DOCX-naar-PPSX-conversie kan worden geautomatiseerd terwijl twee van zijn API's worden gebruikt. Laad uw DOCX met [Aspose.Words for C++](https://products.aspose.com/words/cpp/) en converteer het naar HTML, laad vervolgens de HTML via PowerPoint-manipulatie C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) om een nieuwe presentatie te maken en deze op te slaan als PPSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCX naar PPSX-conversie op C++" %}}
1. Open DOCX-bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klasseverwijzing
2. Converteer DOCX naar HTML met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions) lidfunctie
3. Initialiseer een nieuw [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) object
4. Voeg een AutoVorm toe aan uw dia en voeg AddTextFrame erin toe
5. Laad de HTML-inhoud en schrijf deze in uw presentatiebestand
6. Sla het document op in PPSX-indeling met de methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) en stel Ppsx in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCX file with an instance of Document
Document document = new Document("template.docx");
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"sourceFile.docx");
// save the document in HTML file format
docx->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Laad met een wachtwoord beveiligd DOCX-document via C++" %}}
Afgezien van documentconversie, biedt de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API tal van documentmanipulatiefuncties voor C++-ontwikkelaars. Als uw Microsoft Word DOCX-bestandsindeling met een wachtwoord is beveiligd, kunt u deze nog steeds openen met behulp van de API. Om het versleutelde document te laden, kunt u een speciale constructor-overload gebruiken, die een [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) object accepteert. Dit object bevat de eigenschap Password, waarmee de wachtwoordreeks wordt opgegeven.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docxPassword");
// load thDocumentnt from the local fiDocument by filename:
SharedPtr<Docxument> docx = MakeObject<Docxument>(u"Encrypted.docx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Opmerkingen toevoegen in PPSX-document via C++" %}}
Terwijl u DOCX opslaat als PPSX, kunt u ook [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om meer functies toe te voegen aan uw PPSX-document. U kunt bijvoorbeeld opmerkingen toevoegen aan uw presentatie. De opmerkingen van de presentatiedia zijn gekoppeld aan een bepaalde auteur. De klasse Presentation bevat de verzameling auteurs in ICommentAuthorCollection die verantwoordelijk zijn voor het toevoegen van dia-opmerkingen. Voor elke auteur is er een verzameling opmerkingen in ICommentCollection.
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-pot/" name="DOCX Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-ppt/" name="DOCX Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-potx/" name="DOCX Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-pptx/" name="DOCX Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-pps/" name="DOCX Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-ppsm/" name="DOCX Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-powerpoint/" name="DOCX Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-pptm/" name="DOCX Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-potm/" name="DOCX Tot POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/docx-to-ppsx/" name="DOCX Tot PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}