---
title: Exportera XML till PPSM via C# API
description: .NET API för att konvertera XML till PPSM utan att använda Microsoft Word
url_ignore: /sv/net/conversion/xml-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: PPSM
otherformats: XAML PPS POWERPOINT SWF POTM PPTM OTP PPT PPSX PPSM POTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera XML till PPSM via .NET" h2=".NET API för att exportera XML till PPSM på Windows, macOS och Linux utan att använda Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda ett paket med kraftfulla filformatautomations-API:er [Aspose.Total for .NET](https://products.aspose.com/total/net/) kan du enkelt rendera XML till PPSM i två enkla steg. Genom att använda PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du omvandla XML-filformat till PPTX. Efter det, genom att använda Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), kan du konvertera PPTX till PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API för att konvertera XML till PPSM" %}}
1. Öppna XML-filen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera XML till PPTX genom att använda metoden [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda PPTX-fil genom att använda klassen [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Spara dokumentet i PPSM-format med metoden [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) och ställ in "Ppsm" som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsm", SaveFormat.Ppsm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hämta XMP-metadata från XML-fil via .NET" %}}
När du konverterar XML till PPSM kan du behöva extra XMP-metadatainformation för att prioritera din batchkonverteringsprocess. Till exempel kan du hämta och sortera dina konverteringsdokument baserat på skapandedatum och bearbeta dokumenten därefter. [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/) låter dig komma åt en XML-fils XMP-metadata. För att få en XML-fils metadata kan du skapa ett [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)-objekt och öppna XML-inmatningsfilen. Efter det kan du hämta filens metadata med egenskapen [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad PPSM-fil via .NET" %}}
Genom att använda [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API kan du förbättra funktionerna i din konverteringsapplikation ytterligare. En av funktionerna kan vara att skapa din utdatafil skrivskyddad för att öka säkerheten. API:et låter dig ställa in din PPSM-fil till Read-Only, vilket innebär att användare (efter att de har öppnat presentationen) ser Read-Only-rekommendationen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}