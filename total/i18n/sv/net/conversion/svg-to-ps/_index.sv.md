---
title: C# API för att exportera SVG till PS
description: Konvertera SVG till PS utan att använda Microsoft Word
url: /sv/net/conversion/svg-to-ps/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PS
otherformats: RTF WORDML PCL OTT DOTM XAMLFLOW DOTX PS MARKDOWN DOT MHTML ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera SVG till PS via .NET" h2=".NET API för att exportera SVG till PS på Windows, macOS och Linux utan att använda Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) är ett kraftfullt API för att lägga till dokumentmanipulerings- och konverteringsfunktioner i din .NET-applikation. Genom att använda avancerad PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du konvertera SVG-filformat till DOC. Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera DOC till PS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera SVG till PS" %}}
1. Öppna SVG-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera SVG till Doc genom att använda metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda dokumentfilen genom att använda klassen [Document](https://apireference.aspose.com/words/net/aspose.words/document) av Aspose.Words
4. Spara dokumentet i PS-format med metoden [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Ps som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ps", SaveFormat.Ps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekryptera SVG-fil med ägarlösenord via .NET" %}}
Innan du konverterar SVG till PS, om du vill dekryptera ditt dokument kan du göra det med hjälp av API:et. För att dekryptera PDF-filen måste du först skapa ett [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objekt och öppna SVG med ägarens lösenord. Efter det måste du anropa metoden [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) för Document-objektet. Slutligen, spara den uppdaterade filen med hjälp av Save-metoden för Document-objektet.  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad PS-fil via .NET" %}}
För att skydda din PS från redigering och för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument, kan du också ställa in skyddet för dokumentet med hjälp av API:et. Du kan begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan göras med [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Det låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
```cs
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-ott/" name="SVG Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-mhtml/" name="SVG Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-wordml/" name="SVG Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-dot/" name="SVG Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-odt/" name="SVG Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-rtf/" name="SVG Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-ps/" name="SVG Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-flatopc/" name="SVG Till FLATillPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-pcl/" name="SVG Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-markdown/" name="SVG Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-xamlflow/" name="SVG Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/svg-to-dotx/" name="SVG Till DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}