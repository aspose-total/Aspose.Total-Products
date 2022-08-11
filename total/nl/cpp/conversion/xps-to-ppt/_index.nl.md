---
title: C++ API om XPS naar PPT te converteren
description: Converteer XPS naar PPT via C++ zonder Microsoft Word of Adobe Acrobat Reader te gebruiken
url: /nl/cpp/conversion/xps-to-ppt/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPT
otherformats: PPSX SWF PPSM POTM POT XAML PPS POWERPOINT OTP POTX PPTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS naar PPT binnen C++-toepassingen" h2="Converteer XPS naar PPT binnen uw C++-toepassingen zonder Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bent u een C++-ontwikkelaar die op zoek is naar een toevoeging om de XPS-naar-PPT-conversiefunctie in uw C++-toepassingen te integreren? U kunt het in twee eenvoudige stappen doen. U kunt XPS naar PPTX exporteren met [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Ten tweede, door [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) te gebruiken, kunt u PPTX naar PPT converteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om XPS naar PPT te exporteren" %}}
1. Open het XPS-bestand met behulp van [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) klassereferentie
2. Converteer XPS naar PPTX met behulp van [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) methodefunctie
3. Laad PPTX-document met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) klassereferentie
4. Sla het document op in PPT-formaat met behulp van [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) lidfunctie en stel `Ppt` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xps");
// save XPS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Wijzig wachtwoord van XPS-document via C++" %}}
Tijdens het omzetten van XPS naar PPT kunt u een met een wachtwoord beveiligde XPS openen en ook het wachtwoord wijzigen. Om het wachtwoord van een XPS-bestand te wijzigen, moet u het eigenaarswachtwoord van dat document weten. U kunt een met een wachtwoord beveiligd PDF-document laden met [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) door het eigenaarswachtwoord op te geven en de ChangePasswords-methode te gebruiken om het wachtwoord te wijzigen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Afbeeldingen van internet toevoegen aan PPT-bestand via C++" %}}
Na het converteren van XPS naar PPT, kunt u ook afbeeldingen van internet aan uw uitvoerdocument toevoegen. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ondersteunt bewerkingen met afbeeldingen in deze populaire formaten: JPEG, PNG, BMP, GIF en andere. U kunt een of meerdere afbeeldingen op uw computer toevoegen aan een dia in een presentatie. Deze voorbeeldcode in C++ laat zien hoe u een afbeelding aan een PPT-bestand toevoegt
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPT file
auto pres = System::MakeObject<Presentation>("output.ppt");
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
pres->Save(u"updated.ppt", SaveFormat::Ppt);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-ppsx/" name="XPS Tot PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-swf/" name="XPS Tot SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-ppsm/" name="XPS Tot PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-potm/" name="XPS Tot POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-pot/" name="XPS Tot POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-xaml/" name="XPS Tot XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-pps/" name="XPS Tot PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-powerpoint/" name="XPS Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-otp/" name="XPS Tot OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-potx/" name="XPS Tot POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-pptm/" name="XPS Tot PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/xps-to-ppt/" name="XPS Tot PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}