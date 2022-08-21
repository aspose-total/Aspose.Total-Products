---
title: C++ API för att konvertera XSLFO till PPTM
description: Konvertera XSLFO till PPTM via C++ utan att använda Microsoft Word eller Adobe Acrobat Reader
url: /sv/cpp/conversion/xslfo-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPTM
otherformats: POTX POT ODP POTM PPT PPSX POWERPOINT SWF XAML PPS OTP PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera XSLFO till PPTM inom C++-applikationer" h2="Konvertera XSLFO till PPTM i dina C++-applikationer utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Är du en C++-utvecklare som vill lägga till för att integrera XSLFO till PPTM-konverteringsfunktionen i dina C++-applikationer? Du kan göra det i två enkla steg. Du kan exportera XSLFO till PPTX genom att använda [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). För det andra, genom att använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), kan du konvertera PPTX till PPTM. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att exportera XSLFO till PPTM" %}}
1. Öppna XSLFO-filen med klassreferens [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konvertera XSLFO till PPTX genom att använda metodfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Ladda PPTX-dokument genom att använda klassreferensen [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Spara dokumentet i PPTM-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) och ställ in "Pptm" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pptm format
prs->Save(u"output.pptm", Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändra lösenord för XSLFO-dokument via C++" %}}
I processen att rendera XSLFO till PPTM kan du öppna en lösenordsskyddad XSLFO och även ändra dess lösenord. För att ändra lösenordet för en XSLFO-fil måste du känna till ägarlösenordet för det dokumentet. Du kan ladda lösenordsskyddade PDF-dokument med [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) genom att ange dess ägarlösenord och använda ChangePasswords-metoden för att ändra lösenordet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till bilder från webben i PPTM-fil via C++" %}}
Efter att ha konverterat XSLFO till PPTM kan du också lägga till bilder från webben till ditt utdatadokument. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) stöder operationer med bilder i dessa populära format: JPEG, PNG, BMP, GIF och andra. Du kan lägga till en eller flera bilder på din dator på en bild i en presentation. Den här exempelkoden i C++ visar hur du lägger till en bild i en PPTM-fil
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPTM file
auto pres = System::MakeObject<Presentation>("output.pptm");
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
pres->Save(u"updated.pptm", SaveFormat::Pptm);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-potx/" name="XSLFO Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-pot/" name="XSLFO Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-pptm/" name="XSLFO Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-potm/" name="XSLFO Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-ppt/" name="XSLFO Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-ppsx/" name="XSLFO Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-powerpoint/" name="XSLFO Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-swf/" name="XSLFO Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-xaml/" name="XSLFO Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-pps/" name="XSLFO Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-otp/" name="XSLFO Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/xslfo-to-ppsm/" name="XSLFO Till PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}