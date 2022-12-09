---
title: Converteer XLSM naar POWERPOINT met Java
description: Java API om XLSM naar POWERPOINT te exporteren met Excel of Word
url_ignore: /nl/java/conversion/xlsm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: WORD POWERPOINTX POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om XLSM naar POWERPOINT te exporteren" h2="On Premise Java API om XLSM naar POWERPOINT te exporteren zonder afhankelijk te zijn van Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Het renderen van XLSM naar POWERPOINT is een proces in twee stappen. U gebruikt eerst de API [Aspose.Cells for Java](https://products.aspose.com/cells/java) om het gegeven XLSM-document naar PDF te converteren en vervolgens [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, kunt u uw PDF-document eenvoudig converteren naar POWERPOINT. Beide API's vallen onder de verzameling van [Aspose.Total for Java](https://products.aspose.com/total/java/) automatiseringsbibliotheken voor bestandsindelingen.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hoe XLSM naar POWERPOINT te converteren via Java API" %}}
1. Open het XLSM-bestand met de klasse [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer XLSM naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Sla het document op in POWERPOINT-formaat met [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) methode en stel Powerpoint in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U moet Aspose.Total voor Java rechtstreeks vanuit een op [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere conversie-opties" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsm-to-powerpointx/" name="XLSM Tot POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsm-to-pptx/" name="XLSM Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsm-to-powerpoint/" name="XLSM Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsm-to-word/" name="XLSM Tot WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}