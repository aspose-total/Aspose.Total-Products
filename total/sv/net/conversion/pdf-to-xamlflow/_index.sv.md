---
title: C# API för att exportera PDF till XAMLFLOW
description: Konvertera PDF till XAMLFLOW utan att använda Microsoft Word
url_ignore: /sv/net/conversion/pdf-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XAMLFLOW
otherformats: DOTX XAMLFLOW DOT ODT PCL OTT PS DOTM FLATOPC MARKDOWN RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendera PDF till XAMLFLOW via .NET" h2=".NET API för att exportera PDF till XAMLFLOW på Windows, macOS och Linux utan att använda Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) är ett kraftfullt API för att lägga till dokumentmanipulerings- och konverteringsfunktioner i din .NET-applikation. Genom att använda avancerad PDF Processing API [Aspose.PDF för .NET](https://products.aspose.com/pdf/net/), kan du konvertera PDF-filformat till DOC. Efter det, genom att använda kraftfulla Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera DOC till XAMLFLOW.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera PDF till XAMLFLOW" %}}
1. Öppna PDF-filen med klassen [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konvertera PDF till Doc genom att använda metoden [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Ladda dokumentfilen genom att använda klassen [Document](https://reference.aspose.com/words/net/aspose.words/document) av Aspose.Words
4. Spara dokumentet i XAMLFLOW-format med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Xamlflow som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.pdf");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.xamlflow", SaveFormat.Xamlflow);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dekryptera PDF-fil med ägarlösenord via .NET" %}}
Innan du konverterar PDF till XAMLFLOW, om du vill dekryptera ditt dokument kan du göra det med hjälp av API:et. För att dekryptera PDF-filen måste du först skapa ett [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objekt och öppna PDF med ägarens lösenord. Efter det måste du anropa metoden [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) för Document-objektet. Slutligen, spara den uppdaterade filen med hjälp av Save-metoden för Document-objektet.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.pdf", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Skapa skrivskyddad XAMLFLOW-fil via .NET" %}}
För att skydda din XAMLFLOW från redigering och för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument, kan du också ställa in skyddet för dokumentet med hjälp av API:et. Du kan begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan göras med [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Det låter dig styra hur du begränsar innehållet med hjälp av uppräkningsparametern [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xamlflow", SaveFormat.Xamlflow);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-ott/" name="PDF Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-mhtml/" name="PDF Till MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-wordml/" name="PDF Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-dot/" name="PDF Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-odt/" name="PDF Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-rtf/" name="PDF Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-ps/" name="PDF Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-flatopc/" name="PDF Till FLATillPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-pcl/" name="PDF Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-markdown/" name="PDF Till MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-xamlflow/" name="PDF Till XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/pdf-to-dotx/" name="PDF Till DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}