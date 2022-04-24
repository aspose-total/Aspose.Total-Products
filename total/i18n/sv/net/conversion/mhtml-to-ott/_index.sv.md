---
title: C# API för att exportera MHTML till OTT
description: Konvertera MHTML till OTT utan att använda Microsoft Word
url: /sv/net/conversion/mhtml-to-ott/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: OTT
otherformats: PS MARKDOWN OTT DOTX DOTM FLATOPC DOT WORDML RTF ODT PCL XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera MHTML till OTT via .NET" h2=".NET API för att exportera MHTML till OTT på Windows, macOS och Linux utan att använda Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) är ett kraftfullt API för att lägga till dokumentmanipulerings- och konverteringsfunktioner i din .NET-applikation. Genom att använda avancerad PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du konvertera MHTML-filformat till DOC. Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera DOC till OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera MHTML till OTT" %}}
1. Öppna MHTML-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera MHTML till Doc genom att använda metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda dokumentfilen genom att använda klassen [Document](https://apireference.aspose.com/words/net/aspose.words/document) av Aspose.Words
4. Spara dokumentet i OTT-format med metoden [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Ott som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.mhtml");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekryptera MHTML-fil med ägarlösenord via .NET" %}}
Innan du konverterar MHTML till OTT, om du vill dekryptera ditt dokument kan du göra det med hjälp av API:et. För att dekryptera PDF-filen måste du först skapa ett [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objekt och öppna MHTML med ägarens lösenord. Efter det måste du anropa metoden [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) för Document-objektet. Slutligen, spara den uppdaterade filen med hjälp av Save-metoden för Document-objektet.  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document document = new Document("Decrypt.mhtml", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad OTT-fil via .NET" %}}
För att skydda din OTT från redigering och för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument, kan du också ställa in skyddet för dokumentet med hjälp av API:et. Du kan begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan göras med [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Det låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
```cs
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-ott/" name="MHTML Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-mhtml/" name="MHTML Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-wordml/" name="MHTML Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-dot/" name="MHTML Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-odt/" name="MHTML Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-rtf/" name="MHTML Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-ps/" name="MHTML Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-flatopc/" name="MHTML Till FLATillPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-pcl/" name="MHTML Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-markdown/" name="MHTML Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-xamlflow/" name="MHTML Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/mhtml-to-dotx/" name="MHTML Till DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}