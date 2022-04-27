---
title: Java API för att rendera XML till TSV
description: Exportera XML till TSV via Java API utan att använda Microsoft Excel eller Adobe Reader
url: /sv/java/conversion/xml-to-tsv/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: TSV
otherformats: FODS XLAM XLSB EXCEL TXT SXC XLTM XLSM XLTX MD TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera XML till TSV via Java" h2="Konvertera XML-fil till TSV genom att använda lokalt Java API inom alla Java J2SE, J2EE, J2ME applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du integrera XML till TSV-konverteringsfunktionen i dina Java-applikationer i tvåstegsprocess. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) kan du rendera XML till XLSX. I det andra steget kan du konvertera XLSX till TSV genom att använda Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera XML-fil till TSV via Java" %}}
1. Öppna XML-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XML till XLSX genom att använda [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda XLSX-dokument med hjälp av klassen [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i TSV-format med [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Cells for Java](https://docs.aspose.com/cells/java/ installation/) i din pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Om ditt XML-dokument är lösenordsskyddat kan du inte konvertera det till TSV utan lösenordet. Med hjälp av API:et kan du först öppna det skyddade dokumentet med ett giltigt lösenord och konvertera det efter det. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad XML till TSV via Java" %}}
När du konverterar XML-fil till TSV, kan du också lägga till vattenstämpel till ditt utdata TSV-filformat. För att lägga till en vattenstämpel, skapa en ny arbetsbok för att öppna den konverterade XLSX-filen. Välj kalkylblad via dess index, skapa en form och använd dess addTextEffect-funktion, ställ in färger, transparens och mer. Efter det kan du spara ditt XLSX-dokument som TSV med vattenstämpel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-dif/" name="XML Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xltx/" name="XML Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-md/" name="XML Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-fods/" name="XML Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xltm/" name="XML Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-excel/" name="XML Till EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xlsm/" name="XML Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xlam/" name="XML Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xlt/" name="XML Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-xlsb/" name="XML Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-ods/" name="XML Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xml-to-sxc/" name="XML Till SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}