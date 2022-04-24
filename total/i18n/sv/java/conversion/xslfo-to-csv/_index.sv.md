---
title: Java API för att rendera XSLFO till CSV
description: Exportera XSLFO till CSV via Java API utan att använda Microsoft Excel eller Adobe Reader
url: /sv/java/conversion/xslfo-to-csv/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: CSV
otherformats: XLT XLAM SXC XLSB EXCEL MD TSV DIF TXT XLTX XLTM FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera XSLFO till CSV via Java" h2="Konvertera XSLFO-fil till CSV genom att använda lokalt Java API inom alla Java J2SE, J2EE, J2ME applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du integrera XSLFO till CSV-konverteringsfunktionen i dina Java-applikationer i tvåstegsprocess. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) kan du rendera XSLFO till XLSX. I det andra steget kan du konvertera XLSX till CSV genom att använda Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera XSLFO-fil till CSV via Java" %}}
1. Öppna XSLFO-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XSLFO till XLSX genom att använda [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda XLSX-dokument med hjälp av klassen [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i CSV-format med [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Cells for Java](https://docs.aspose.com/cells/java/ installation/) i din pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Om ditt XSLFO-dokument är lösenordsskyddat kan du inte konvertera det till CSV utan lösenordet. Med hjälp av API:et kan du först öppna det skyddade dokumentet med ett giltigt lösenord och konvertera det efter det. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad XSLFO till CSV via Java" %}}
När du konverterar XSLFO-fil till CSV, kan du också lägga till vattenstämpel till ditt utdata CSV-filformat. För att lägga till en vattenstämpel, skapa en ny arbetsbok för att öppna den konverterade XLSX-filen. Välj kalkylblad via dess index, skapa en form och använd dess addTextEffect-funktion, ställ in färger, transparens och mer. Efter det kan du spara ditt XLSX-dokument som CSV med vattenstämpel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-dif/" name="XSLFO Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-xltx/" name="XSLFO Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-md/" name="XSLFO Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-fods/" name="XSLFO Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-xltm/" name="XSLFO Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-excel/" name="XSLFO Till EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-xlsm/" name="XSLFO Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-xlam/" name="XSLFO Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-xlt/" name="XSLFO Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-xlsb/" name="XSLFO Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-ods/" name="XSLFO Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xslfo-to-sxc/" name="XSLFO Till SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}