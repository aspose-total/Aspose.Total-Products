---
title: Konvertera XLSM till WORD med Java
description: Java API för att exportera XLSM till WORD med hjälp av Excel eller Word
url_ignore: /sv/java/conversion/xlsm-to-word/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: WORD
otherformats: WORD WORDX PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att exportera XLSM till WORD" h2="On Premise Java API för att exportera XLSM till WORD utan att förlita sig på Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att rendera XLSM till WORD är en process i två steg. Du använder först [Aspose.Cells for Java](https://products.aspose.com/cells/java) API för att konvertera det givna XLSM-dokumentet till PDF och sedan genom att använda [Aspose.Pdf för Java](https://products.aspose.com/pdf/java) API kan du enkelt konvertera ditt PDF-dokument till WORD. Båda API:erna ingår i samlingen av [Aspose.Total for Java](https://products.aspose.com/total/java/) filformatsautomatiseringsbibliotek.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar XLSM till WORD via Java API" %}}
1. Öppna XLSM-filen med klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera XLSM till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Spara dokumentet i WORD-format med [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) och ställ in Word som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du måste använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xlsm-to-wordx/" name="XLSM Till WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xlsm-to-pptx/" name="XLSM Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xlsm-to-powerpoint/" name="XLSM Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xlsm-to-word/" name="XLSM Till WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}