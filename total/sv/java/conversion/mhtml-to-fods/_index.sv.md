---
title: Java API för att rendera MHTML till FODS
description: Exportera MHTML till FODS via Java API utan att använda Microsoft Excel eller Adobe Reader
url_ignore: /sv/java/conversion/mhtml-to-fods/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: FODS
otherformats: MD SXC FODS TSV XLT TXT XLSB XLSM EXCEL DIF XLAM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera MHTML till FODS via Java" h2="Konvertera MHTML-fil till FODS genom att använda lokalt Java API inom alla Java J2SE, J2EE, J2ME applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du integrera MHTML till FODS-konverteringsfunktionen i dina Java-applikationer i tvåstegsprocess. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) kan du rendera MHTML till XLSX. I det andra steget kan du konvertera XLSX till FODS genom att använda Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera MHTML-fil till FODS via Java" %}}
1. Öppna MHTML-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera MHTML till XLSX genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
3. Ladda XLSX-dokument med hjälp av klassen [Arbetsbok](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i FODS-format med [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera [Aspose.PDF för Java](https://docs.aspose.com/pdf/java/installation/) och [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) i din pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Om ditt MHTML-dokument är lösenordsskyddat kan du inte konvertera det till FODS utan lösenordet. Med hjälp av API:et kan du först öppna det skyddade dokumentet med ett giltigt lösenord och konvertera det efter det. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad MHTML till FODS via Java" %}}
När du konverterar MHTML-fil till FODS, kan du också lägga till vattenstämpel till ditt utdata FODS-filformat. För att lägga till en vattenstämpel, skapa en ny arbetsbok för att öppna den konverterade XLSX-filen. Välj kalkylblad via dess index, skapa en form och använd dess addTextEffect-funktion, ställ in färger, transparens och mer. Efter det kan du spara ditt XLSX-dokument som FODS med vattenstämpel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}