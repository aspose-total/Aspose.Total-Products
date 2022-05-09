---
title: Konvertera XLTX till PPTX med Java
description: Java API för att exportera XLTX till PPTX med hjälp av Excel eller Word
url_ignore: /sv/java/conversion/xltx-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: POWERPOINT WORD PPTXX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API för att exportera XLTX till PPTX" h2="On Premise Java API för att exportera XLTX till PPTX utan att förlita sig på Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att rendera XLTX till PPTX är en process i två steg. Du använder först [Aspose.Cells for Java](https://products.aspose.com/cells/java) API för att konvertera det givna XLTX-dokumentet till PDF och sedan genom att använda [Aspose.Pdf för Java](https://products.aspose.com/pdf/java) API kan du enkelt konvertera ditt PDF-dokument till PPTX. Båda API:erna ingår i samlingen av [Aspose.Total for Java](https://products.aspose.com/total/java/) filformatsautomatiseringsbibliotek.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar XLTX till PPTX via Java API" %}}
1. Öppna XLTX-filen med klassen [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konvertera XLTX till PDF och ställ in SaveFormat till AUTO
3. Ladda den konverterade PDF-filen med klassen [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Spara dokumentet i PPTX-format med [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) och ställ in Pptx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du måste använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xltx-to-pptxx/" name="XLTX Till PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xltx-to-pptx/" name="XLTX Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xltx-to-powerpoint/" name="XLTX Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/xltx-to-word/" name="XLTX Till WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}