---
title: Converteer XLSX naar POWERPOINT met Java
description: Java API om XLSX naar POWERPOINT te exporteren met Excel of Word
url_ignore: /nl/java/conversion/xlsx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: POWERPOINTX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om XLSX naar POWERPOINT te exporteren" h2="On Premise Java API om XLSX naar POWERPOINT te exporteren zonder afhankelijk te zijn van Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Het renderen van XLSX naar POWERPOINT is een proces in twee stappen. U gebruikt eerst de API [Aspose.Cells for Java](https://products.aspose.com/cells/java) om het gegeven XLSX-document naar PDF te converteren en vervolgens [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, kunt u uw PDF-document eenvoudig converteren naar POWERPOINT. Beide API's vallen onder de verzameling van [Aspose.Total for Java](https://products.aspose.com/total/java/) automatiseringsbibliotheken voor bestandsindelingen.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hoe XLSX naar POWERPOINT te converteren via Java API" %}}
1. Open het XLSX-bestand met de klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer XLSX naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Sla het document op in POWERPOINT-formaat met [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) methode en stel Powerpoint in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U moet Aspose.Total voor Java rechtstreeks vanuit een op [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsx-to-powerpointx/" name="XLSX Tot POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsx-to-pptx/" name="XLSX Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsx-to-powerpoint/" name="XLSX Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/xlsx-to-word/" name="XLSX Tot WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}