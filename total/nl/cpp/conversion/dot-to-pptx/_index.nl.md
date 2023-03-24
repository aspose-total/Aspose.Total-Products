---
title: Converteer DOT naar PPTX via C++ of met gratis Online Converter
description: Exporteer DOT naar PPTX in uw C++-toepassingen zonder Microsoft Word of PowerPoint te gebruiken of online. Test de gratis POT naar CSV online converter snel voordat u de code integreert.

family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: PPTX
otherformats: PPT ODP POTM POTX PPSM PPTM POT PPS POWERPOINT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om DOT naar PPTX te converteren of online-app" h2="Exporteer DOT naar PPTX binnen uw C++-toepassingen zonder Microsoft Word&reg; of PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) bestaat uit krachtige API's voor bestandsautomatisering waarmee de DOT-naar-PPTX-conversie kan worden geautomatiseerd terwijl twee van zijn API's worden gebruikt. Laad uw DOT met [Aspose.Words for C++](https://products.aspose.com/words/cpp/) en converteer het naar HTML, laad vervolgens de HTML via PowerPoint-manipulatie C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) om een nieuwe presentatie te maken en deze op te slaan als PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOT naar PPTX-conversie op C++" %}}
1. Open DOT-bestand met behulp van [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument) klasseverwijzing
2. Converteer DOT naar HTML met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_stdbasicostream_saveoptions) lidfunctie
3. Initialiseer een nieuw [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) object
4. Voeg een AutoVorm toe aan uw dia en voeg AddTextFrame erin toe
5. Laad de HTML-inhoud en schrijf deze in uw presentatiebestand
6. Sla het dotument op in PPTX-indeling met de methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) en stel Pptx in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOT file with an instance of Dotument
Dotument dotument = new Dotument("template.dot");
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"sourceFile.dot");
// save the dotument in HTML file format
dot->Save(u"HtmlOutput.HTML");
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

<h3>Gratis online converter voor DOT naar PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=dot" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Laad met een wachtwoord beveiligd DOT-dotument via C++" %}}
Afgezien van dotumentconversie, biedt de [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API tal van dotumentmanipulatiefuncties voor C++-ontwikkelaars. Als uw Microsoft Word DOT-bestandsindeling met een wachtwoord is beveiligd, kunt u deze nog steeds openen met behulp van de API. Om het versleutelde dotument te laden, kunt u een speciale constructor-overload gebruiken, die een [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) object accepteert. Dit object bevat de eigenschap Password, waarmee de wachtwoordreeks wordt opgegeven.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotument, the password is passed to the dotument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotPassword");
// load the dotument from the local file system by filename:
SharedPtr<Dotument> dot = MakeObject<Dotument>(u"Encrypted.dot", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Opmerkingen toevoegen in PPTX-dotument via C++" %}}
Terwijl u DOT opslaat als PPTX, kunt u ook [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om meer functies toe te voegen aan uw PPTX-dotument. U kunt bijvoorbeeld opmerkingen toevoegen aan uw presentatie. De opmerkingen van de presentatiedia zijn gekoppeld aan een bepaalde auteur. De klasse Presentation bevat de verzameling auteurs in ICommentAuthorCollection die verantwoordelijk zijn voor het toevoegen van dia-opmerkingen. Voor elke auteur is er een verzameling opmerkingen in ICommentCollection.
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}