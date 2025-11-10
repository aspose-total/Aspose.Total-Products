---
title: Java API för att rendera XSLFO till FODS
description: Exportera XSLFO till FODS via Java API utan att använda Microsoft Excel eller Adobe Reader
url_ignore: /sv/java/conversion/xslfo-to-fods/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: FODS
otherformats: XLAM ODS FODS XLTM XLT TSV SXC MD EXCEL XLTX XLSM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera XSLFO till FODS via Java" h2="Konvertera XSLFO-fil till FODS genom att använda lokalt Java API inom alla Java J2SE, J2EE, J2ME applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du integrera XSLFO till FODS-konverteringsfunktionen i dina Java-applikationer i tvåstegsprocess. För det första, genom att använda [Aspose.PDF för Java](https://products.aspose.com/pdf/java/) kan du rendera XSLFO till XLSX. I det andra steget kan du konvertera XLSX till FODS genom att använda Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera XSLFO-fil till FODS via Java" %}}
1. Öppna XSLFO-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konvertera XSLFO till XLSX genom att använda [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metod
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
Om ditt XSLFO-dokument är lösenordsskyddat kan du inte konvertera det till FODS utan lösenordet. Med hjälp av API:et kan du först öppna det skyddade dokumentet med ett giltigt lösenord och konvertera det efter det. För att öppna den krypterade filen kan du initiera en ny instans av [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) klass och skicka filnamn och lösenord som argument.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad XSLFO till FODS via Java" %}}
När du konverterar XSLFO-fil till FODS, kan du också lägga till vattenstämpel till ditt utdata FODS-filformat. För att lägga till en vattenstämpel, skapa en ny arbetsbok för att öppna den konverterade XLSX-filen. Välj kalkylblad via dess index, skapa en form och använd dess addTextEffect-funktion, ställ in färger, transparens och mer. Efter det kan du spara ditt XLSX-dokument som FODS med vattenstämpel. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Konvertering av XSLFO-filer till **FODS (Flat OpenDocument Spreadsheet)**-format stöder öppen källkods kontorspaket som LibreOffice och OpenOffice. FODS möjliggör lätta, redigerbara kalkylblad baserade på XML som passar för samarbetsmiljöer.



{{% blocks/products/pf/agp/feature-section-col title="Nyckelanvändningsfall" %}}



* Dela XSLFO-genererade budgetblad med användare av öppen källkodskontor.

* Arkivering av rapporter i ett öppet, standardiserat kalkylbladsformat.

* Förbereda projektspårningsblad för samarbete över plattformar.

* Konvertera tekniska XSLFO-tabeller till redigerbara FODS-kalkylblad.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatiseringsscenario" %}}



* Batchkonvertering av XSLFO till FODS för öppna rapporteringspipeliner.

* Integrering i dokumenthanteringssystem som stöder FODS.

* Schemalagd export för samarbetsprojektdashboardar.

* Automatisk konvertering av XSLFO-analyserapporter till FODS-format.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}