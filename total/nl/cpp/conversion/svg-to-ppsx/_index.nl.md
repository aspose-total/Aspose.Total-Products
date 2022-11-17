---
title: C++ API om SVG naar PPSX te converteren
description: Converteer SVG naar PPSX via C++ zonder Microsoft Word of Adobe Acrobat Reader te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: PPSX
otherformats: SWF PPSM POTM POTX PPT PPTM POWERPOINT POT XAML OTP PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render SVG naar PPSX binnen C++-toepassingen" h2="Converteer SVG naar PPSX binnen uw C++-toepassingen zonder Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bent u een C++-ontwikkelaar die op zoek is naar een toevoeging om de SVG-naar-PPSX-conversiefunctie in uw C++-toepassingen te integreren? U kunt het in twee eenvoudige stappen doen. U kunt SVG naar PPTX exporteren met [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Ten tweede, door [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) te gebruiken, kunt u PPTX naar PPSX converteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om SVG naar PPSX te exporteren" %}}
1. Open het SVG-bestand met behulp van [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klassereferentie
2. Converteer SVG naar PPTX met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) methodefunctie
3. Laad PPTX-document met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) klassereferentie
4. Sla het document op in PPSX-formaat met behulp van [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) lidfunctie en stel `Ppsx` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class
auto doc = MakeObject<Document>(u"template.svg");
// save SVG as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Wijzig wachtwoord van SVG-document via C++" %}}
Tijdens het omzetten van SVG naar PPSX kunt u een met een wachtwoord beveiligde SVG openen en ook het wachtwoord wijzigen. Om het wachtwoord van een SVG-bestand te wijzigen, moet u het eigenaarswachtwoord van dat document weten. U kunt een met een wachtwoord beveiligd PDF-document laden met [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) door het eigenaarswachtwoord op te geven en de ChangePasswords-methode te gebruiken om het wachtwoord te wijzigen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Afbeeldingen van internet toevoegen aan PPSX-bestand via C++" %}}
Na het converteren van SVG naar PPSX, kunt u ook afbeeldingen van internet aan uw uitvoerdocument toevoegen. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ondersteunt bewerkingen met afbeeldingen in deze populaire formaten: JPEG, PNG, BMP, GIF en andere. U kunt een of meerdere afbeeldingen op uw computer toevoegen aan een dia in een presentatie. Deze voorbeeldcode in C++ laat zien hoe u een afbeelding aan een PPSX-bestand toevoegt
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPSX file
auto pres = System::MakeObject<Presentation>("output.ppsx");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.ppsx", SaveFormat::Ppsx);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-swf/" name="SVG Tot SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-ppsm/" name="SVG Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-potm/" name="SVG Tot POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-potx/" name="SVG Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-ppt/" name="SVG Tot PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-pptm/" name="SVG Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-powerpoint/" name="SVG Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-pot/" name="SVG Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-xaml/" name="SVG Tot XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-otp/" name="SVG Tot OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-pps/" name="SVG Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/svg-to-ppsx/" name="SVG Tot PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}