---
title: Exportera CGM till ODP via C# API
description: .NET API för att konvertera CGM till ODP utan att använda Microsoft Word
url: /sv/net/conversion/cgm-to-odp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODP
otherformats: POT PPSX SWF POWERPOINT OTP POTM PPT PPS POTX XAML PPSM PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera CGM till ODP via .NET" h2=".NET API för att exportera CGM till ODP på Windows, macOS och Linux utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda ett paket med kraftfulla filformatautomations-API:er [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt rendera CGM till ODP i två enkla steg. Genom att använda PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du omvandla CGM-filformat till PPTX. Efter det, genom att använda Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), kan du konvertera PPTX till ODP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API för att konvertera CGM till ODP" %}}
1. Öppna CGM-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera CGM till PPTX genom att använda metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda PPTX-fil genom att använda klassen [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Spara dokumentet i ODP-format med metoden [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) och ställ in "Odp" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hämta XMP-metadata från CGM-fil via .NET" %}}
När du konverterar CGM till ODP kan du behöva extra XMP-metadatainformation för att prioritera din batchkonverteringsprocess. Till exempel kan du hämta och sortera dina konverteringsdokument baserat på skapandedatum och bearbeta dokumenten därefter. [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/) låter dig komma åt en CGM-fils XMP-metadata. För att få en CGM-fils metadata kan du skapa ett [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-objekt och öppna CGM-inmatningsfilen. Efter det kan du hämta filens metadata med egenskapen [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad ODP-fil via .NET" %}}
Genom att använda [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API kan du förbättra funktionerna i din konverteringsapplikation ytterligare. En av funktionerna kan vara att skapa din utdatafil skrivskyddad för att öka säkerheten. API:et låter dig ställa in din ODP-fil till Read-Only, vilket innebär att användare (efter att de har öppnat presentationen) ser Read-Only-rekommendationen. 
```cs
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-pot/" name="CGM Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-ppsx/" name="CGM Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-swf/" name="CGM Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-powerpoint/" name="CGM Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-otp/" name="CGM Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-potm/" name="CGM Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-ppt/" name="CGM Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-pps/" name="CGM Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-potx/" name="CGM Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-xaml/" name="CGM Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-ppsm/" name="CGM Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/cgm-to-pptm/" name="CGM Till PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}