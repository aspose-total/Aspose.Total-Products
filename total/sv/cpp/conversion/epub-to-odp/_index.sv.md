---
title: C++ API för att konvertera EPUB till ODP
description: Konvertera EPUB till ODP via C++ utan att använda Microsoft Word eller Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: ODP
otherformats: PPSX XAML POWERPOINT SWF PPS POTM POTX PPTM POT PPT PPSM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera EPUB till ODP inom C++-applikationer" h2="Konvertera EPUB till ODP i dina C++-applikationer utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Är du en C++-utvecklare som vill lägga till för att integrera EPUB till ODP-konverteringsfunktionen i dina C++-applikationer? Du kan göra det i två enkla steg. Du kan exportera EPUB till PPTX genom att använda [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). För det andra, genom att använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), kan du konvertera PPTX till ODP. Båda API:erna kommer under paketet [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att exportera EPUB till ODP" %}}
1. Öppna EPUB-filen med klassreferens [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konvertera EPUB till PPTX genom att använda metodfunktionen [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Ladda PPTX-dokument genom att använda klassreferensen [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Spara dokumentet i ODP-format med hjälp av medlemsfunktionen [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) och ställ in "Odp" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class
auto doc = MakeObject<Document>(u"template.epub");
// save EPUB as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändra lösenord för EPUB-dokument via C++" %}}
I processen att rendera EPUB till ODP kan du öppna en lösenordsskyddad EPUB och även ändra dess lösenord. För att ändra lösenordet för en EPUB-fil måste du känna till ägarlösenordet för det dokumentet. Du kan ladda lösenordsskyddade PDF-dokument med [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) genom att ange dess ägarlösenord och använda ChangePasswords-metoden för att ändra lösenordet.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till bilder från webben i ODP-fil via C++" %}}
Efter att ha konverterat EPUB till ODP kan du också lägga till bilder från webben till ditt utdatadokument. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) stöder operationer med bilder i dessa populära format: JPEG, PNG, BMP, GIF och andra. Du kan lägga till en eller flera bilder på din dator på en bild i en presentation. Den här exempelkoden i C++ visar hur du lägger till en bild i en ODP-fil
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a ODP file
auto pres = System::MakeObject<Presentation>("output.odp");
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
pres->Save(u"updated.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-ppsx/" name="EPUB Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-xaml/" name="EPUB Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-powerpoint/" name="EPUB Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-swf/" name="EPUB Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-pps/" name="EPUB Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-potm/" name="EPUB Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-potx/" name="EPUB Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-pptm/" name="EPUB Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-pot/" name="EPUB Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-ppt/" name="EPUB Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-ppsm/" name="EPUB Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/epub-to-otp/" name="EPUB Till OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}