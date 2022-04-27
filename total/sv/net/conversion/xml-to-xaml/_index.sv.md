---
title: Exportera XML till XAML via C# API
description: .NET API för att konvertera XML till XAML utan att använda Microsoft Word
url: /sv/net/conversion/xml-to-xaml/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: XAML
otherformats: POTX PPT SWF PPSM OTP POTM PPS POWERPOINT POT XAML PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera XML till XAML via .NET" h2=".NET API för att exportera XML till XAML på Windows, macOS och Linux utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda ett paket med kraftfulla filformatautomations-API:er [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt rendera XML till XAML i två enkla steg. Genom att använda PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du omvandla XML-filformat till PPTX. Efter det, genom att använda Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), kan du konvertera PPTX till XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API för att konvertera XML till XAML" %}}
1. Öppna XML-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera XML till PPTX genom att använda metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda PPTX-fil genom att använda klassen [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Spara dokumentet i XAML-format med metoden [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) och ställ in "Xaml" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.xaml", SaveFormat.Xaml);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hämta XMP-metadata från XML-fil via .NET" %}}
När du konverterar XML till XAML kan du behöva extra XMP-metadatainformation för att prioritera din batchkonverteringsprocess. Till exempel kan du hämta och sortera dina konverteringsdokument baserat på skapandedatum och bearbeta dokumenten därefter. [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/) låter dig komma åt en XML-fils XMP-metadata. För att få en XML-fils metadata kan du skapa ett [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-objekt och öppna XML-inmatningsfilen. Efter det kan du hämta filens metadata med egenskapen [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad XAML-fil via .NET" %}}
Genom att använda [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API kan du förbättra funktionerna i din konverteringsapplikation ytterligare. En av funktionerna kan vara att skapa din utdatafil skrivskyddad för att öka säkerheten. API:et låter dig ställa in din XAML-fil till Read-Only, vilket innebär att användare (efter att de har öppnat presentationen) ser Read-Only-rekommendationen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-pot/" name="XML Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ppsx/" name="XML Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-swf/" name="XML Till SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-powerpoint/" name="XML Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-otp/" name="XML Till OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-potm/" name="XML Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ppt/" name="XML Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-pps/" name="XML Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-potx/" name="XML Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xaml/" name="XML Till XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ppsm/" name="XML Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-pptm/" name="XML Till PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}