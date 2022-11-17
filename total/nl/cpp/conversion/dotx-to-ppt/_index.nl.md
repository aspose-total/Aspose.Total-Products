---
title: Converteer DOTX naar PPT via C++
description: Exporteer DOTX naar PPT in uw C++-toepassingen zonder Microsoft Word of PowerPoint te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: PPT
otherformats: POTX PPS PPTM POWERPOINT PPSM POT PPSX PPTX ODP POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om DOTX naar PPT te converteren" h2="Exporteer DOTX naar PPT binnen uw C++-toepassingen zonder Microsoft Word&reg; of PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bestaat uit krachtige API's voor bestandsautomatisering waarmee de DOTX-naar-PPT-conversie kan worden geautomatiseerd terwijl twee van zijn API's worden gebruikt. Laad uw DOTX met [Aspose.Words for C++](https://products.aspose.com/words/cpp/) en converteer het naar HTML, laad vervolgens de HTML via PowerPoint-manipulatie C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) om een nieuwe presentatie te maken en deze op te slaan als PPT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX naar PPT-conversie op C++" %}}
1. Open DOTX-bestand met behulp van [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) klasseverwijzing
2. Converteer DOTX naar HTML met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions) lidfunctie
3. Initialiseer een nieuw [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) object
4. Voeg een AutoVorm toe aan uw dia en voeg AddTextFrame erin toe
5. Laad de HTML-inhoud en schrijf deze in uw presentatiebestand
6. Sla het dotxument op in PPT-indeling met de methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) en stel Ppt in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTX file with an instance of Dotxument
Dotxument dotxument = new Dotxument("template.dotx");
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"sourceFile.dotx");
// save the dotxument in HTML file format
dotx->Save(u"HtmlOutput.HTML");
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

{{% blocks/products/pf/feature-page-section  h2="Laad met een wachtwoord beveiligd DOTX-dotxument via C++" %}}
Afgezien van dotxumentconversie, biedt de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API tal van dotxumentmanipulatiefuncties voor C++-ontwikkelaars. Als uw Microsoft Word DOTX-bestandsindeling met een wachtwoord is beveiligd, kunt u deze nog steeds openen met behulp van de API. Om het versleutelde dotxument te laden, kunt u een speciale constructor-overload gebruiken, die een [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) object accepteert. Dit object bevat de eigenschap Password, waarmee de wachtwoordreeks wordt opgegeven.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotxument, the password is passed to the dotxument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotxPassword");
// load the dotxument from the local file system by filename:
SharedPtr<Dotxument> dotx = MakeObject<Dotxument>(u"Encrypted.dotx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Opmerkingen toevoegen in PPT-dotxument via C++" %}}
Terwijl u DOTX opslaat als PPT, kunt u ook [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om meer functies toe te voegen aan uw PPT-dotxument. U kunt bijvoorbeeld opmerkingen toevoegen aan uw presentatie. De opmerkingen van de presentatiedia zijn gekoppeld aan een bepaalde auteur. De klasse Presentation bevat de verzameling auteurs in ICommentAuthorCollection die verantwoordelijk zijn voor het toevoegen van dia-opmerkingen. Voor elke auteur is er een verzameling opmerkingen in ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-potx/" name="DOTX Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-pps/" name="DOTX Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-pptm/" name="DOTX Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-powerpoint/" name="DOTX Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-ppsm/" name="DOTX Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-pot/" name="DOTX Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-ppsx/" name="DOTX Tot PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-pptx/" name="DOTX Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-ppt/" name="DOTX Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/dotx-to-potm/" name="DOTX Tot POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}