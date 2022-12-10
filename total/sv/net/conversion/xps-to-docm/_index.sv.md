---
title: C# API för att exportera XPS till DOCM
description: Konvertera XPS till DOCM utan att använda Microsoft Word
url_ignore: /sv/net/conversion/xps-to-docm/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: DOCM
otherformats: DOT FLATOPC DOTM MHTML WORDML ODT PS MARKDOWN RTF PCL OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera XPS till DOCM via .NET" h2=".NET API för att exportera XPS till DOCM på Windows, macOS och Linux utan att använda Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) är ett kraftfullt API för att lägga till dokumentmanipulerings- och konverteringsfunktioner i din .NET-applikation. Genom att använda avancerad PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du konvertera XPS-filformat till DOC. Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera DOC till DOCM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera XPS till DOCM" %}}
1. Öppna XPS-filen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera XPS till Doc genom att använda metoden [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda dokumentfilen genom att använda klassen [Document](https://reference.aspose.com/words/net/aspose.words/document) av Aspose.Words
4. Spara dokumentet i DOCM-format med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Docm som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.xps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.docm", SaveFormat.Docm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekryptera XPS-fil med ägarlösenord via .NET" %}}
Innan du konverterar XPS till DOCM, om du vill dekryptera ditt dokument kan du göra det med hjälp av API:et. För att dekryptera PDF-filen måste du först skapa ett [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objekt och öppna XPS med ägarens lösenord. Efter det måste du anropa metoden [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) för Document-objektet. Slutligen, spara den uppdaterade filen med hjälp av Save-metoden för Document-objektet.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.xps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad DOCM-fil via .NET" %}}
För att skydda din DOCM från redigering och för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument, kan du också ställa in skyddet för dokumentet med hjälp av API:et. Du kan begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan göras med [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Det låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docm", SaveFormat.Docm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-ott/" name="XPS Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-mhtml/" name="XPS Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-wordml/" name="XPS Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-dot/" name="XPS Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-odt/" name="XPS Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-rtf/" name="XPS Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-ps/" name="XPS Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-flatopc/" name="XPS Till FLATillPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-pcl/" name="XPS Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-markdown/" name="XPS Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-xamlflow/" name="XPS Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xps-to-dotx/" name="XPS Till DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}