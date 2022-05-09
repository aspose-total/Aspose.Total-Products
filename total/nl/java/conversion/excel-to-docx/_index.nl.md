---
title: Converteer EXCEL naar DOCX met Java
description: Java API om EXCEL naar DOCX te exporteren met Excel of Word
url_ignore: /nl/java/conversion/excel-to-docx/
family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: DOCXX
otherformats: POWERPOINT WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om EXCEL naar DOCX te exporteren" h2="On Premise Java API om EXCEL naar DOCX te exporteren zonder afhankelijk te zijn van Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Het renderen van EXCEL naar DOCX is een proces in twee stappen. U gebruikt eerst de API [Aspose.Cells for Java](https://products.aspose.com/cells/java) om het gegeven EXCEL-Document naar PDF te converteren en vervolgens [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, kunt u uw PDF-Document eenvoudig converteren naar DOCX. Beide API's vallen onder de verzameling van [Aspose.Total for Java](https://products.aspose.com/total/java/) automatiseringsbibliotheken voor bestandsindelingen.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hoe EXCEL naar DOCX te converteren via Java API" %}}
1. Open het EXCEL-bestand met de klasse [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converteer EXCEL naar PDF en stel SaveFormat in op AUTO
3. Laad het geconverteerde PDF-bestand met de klasse [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Sla het Document op in DOCX-formaat met [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) methode en stel Docx in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U moet Aspose.Total voor Java rechtstreeks vanuit een op [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere conversie-opties" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/excel-to-docxx/" name="EXCEL Tot DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/excel-to-pptx/" name="EXCEL Tot PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/excel-to-powerpoint/" name="EXCEL Tot POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/net/conversion/excel-to-word/" name="EXCEL Tot WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}