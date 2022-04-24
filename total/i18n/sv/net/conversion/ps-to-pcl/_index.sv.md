---
title: C# API för att exportera PS till PCL
description: Konvertera PS till PCL utan att använda Microsoft Word
url: /sv/net/conversion/ps-to-pcl/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PCL
otherformats: MHTML WORDML MARKDOWN DOTM FLATOPC XAMLFLOW ODT DOTX RTF PCL OTT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera PS till PCL via .NET" h2=".NET API för att exportera PS till PCL på Windows, macOS och Linux utan att använda Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) är ett kraftfullt API för att lägga till dokumentmanipulerings- och konverteringsfunktioner i din .NET-applikation. Genom att använda avancerad PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du konvertera PS-filformat till DOC. Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera DOC till PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera PS till PCL" %}}
1. Öppna PS-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera PS till Doc genom att använda metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda dokumentfilen genom att använda klassen [Document](https://apireference.aspose.com/words/net/aspose.words/document) av Aspose.Words
4. Spara dokumentet i PCL-format med metoden [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Pcl som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.ps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekryptera PS-fil med ägarlösenord via .NET" %}}
Innan du konverterar PS till PCL, om du vill dekryptera ditt dokument kan du göra det med hjälp av API:et. För att dekryptera PDF-filen måste du först skapa ett [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objekt och öppna PS med ägarens lösenord. Efter det måste du anropa metoden [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) för Document-objektet. Slutligen, spara den uppdaterade filen med hjälp av Save-metoden för Document-objektet.  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document document = new Document("Decrypt.ps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad PCL-fil via .NET" %}}
För att skydda din PCL från redigering och för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument, kan du också ställa in skyddet för dokumentet med hjälp av API:et. Du kan begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan göras med [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Det låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
```cs
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-ott/" name="PS Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-mhtml/" name="PS Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-wordml/" name="PS Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-dot/" name="PS Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-odt/" name="PS Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-rtf/" name="PS Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-ps/" name="PS Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-flatopc/" name="PS Till FLATillPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-pcl/" name="PS Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-markdown/" name="PS Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-xamlflow/" name="PS Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ps-to-dotx/" name="PS Till DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}