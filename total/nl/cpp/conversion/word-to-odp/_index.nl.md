---
title: Converteer WORD naar ODP via C++
description: Exporteer WORD naar ODP in uw C++-toepassingen zonder Microsoft Word of PowerPoint te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: ODP
otherformats: POTX PPSX PPT PPSM POT PPS PPTX PPTM POWERPOINT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om WORD naar ODP te converteren" h2="Exporteer WORD naar ODP binnen uw C++-toepassingen zonder Microsoft Word&reg; of PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bestaat uit krachtige API's voor bestandsautomatisering waarmee de WORD-naar-ODP-conversie kan worden geautomatiseerd terwijl twee van zijn API's worden gebruikt. Laad uw WORD met [Aspose.Words for C++](https://products.aspose.com/words/cpp/) en converteer het naar HTML, laad vervolgens de HTML via PowerPoint-manipulatie C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) om een nieuwe presentatie te maken en deze op te slaan als ODP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORD naar ODP-conversie op C++" %}}
1. Open WORD-bestand met behulp van [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument) klasseverwijzing
2. Converteer WORD naar HTML met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_stdbasicostream_saveoptions) lidfunctie
3. Initialiseer een nieuw [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) object
4. Voeg een AutoVorm toe aan uw dia en voeg AddTextFrame erin toe
5. Laad de HTML-inhoud en schrijf deze in uw presentatiebestand
6. Sla het wordument op in ODP-indeling met de methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) en stel Odp in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
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
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Laad met een wachtwoord beveiligd WORD-wordument via C++" %}}
Afgezien van wordumentconversie, biedt de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API tal van wordumentmanipulatiefuncties voor C++-ontwikkelaars. Als uw Microsoft Word WORD-bestandsindeling met een wachtwoord is beveiligd, kunt u deze nog steeds openen met behulp van de API. Om het versleutelde wordument te laden, kunt u een speciale constructor-overload gebruiken, die een [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) object accepteert. Dit object bevat de eigenschap Password, waarmee de wachtwoordreeks wordt opgegeven.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordument, the password is passed to the wordument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordPassword");
// load the wordument from the local file system by filename:
SharedPtr<Wordument> word = MakeObject<Wordument>(u"Encrypted.wordx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Opmerkingen toevoegen in ODP-wordument via C++" %}}
Terwijl u WORD opslaat als ODP, kunt u ook [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om meer functies toe te voegen aan uw ODP-wordument. U kunt bijvoorbeeld opmerkingen toevoegen aan uw presentatie. De opmerkingen van de presentatiedia zijn gekoppeld aan een bepaalde auteur. De klasse Presentation bevat de verzameling auteurs in ICommentAuthorCollection die verantwoordelijk zijn voor het toevoegen van dia-opmerkingen. Voor elke auteur is er een verzameling opmerkingen in ICommentCollection.
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
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-potx/" name="WORDX Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-ppsx/" name="WORDX Tot PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-ppt/" name="WORDX Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-ppsm/" name="WORDX Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-pot/" name="WORDX Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-pps/" name="WORDX Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-pptx/" name="WORDX Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-pptm/" name="WORDX Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-powerpoint/" name="WORDX Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/wordx-to-potm/" name="WORDX Tot POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}