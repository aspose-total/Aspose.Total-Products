---
title: Convert ODS to POWERPOINT using Java 
description: Convert ODS to POWERPOINT using On Premise Java API
url: /java/conversion/ods-to-powerpoint/
family: total
platformtag: java
feature: conversion
informat: ODS
outformat: PPTX
otherformats: DOCX WORD PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert ODS to POWERPOINT via Java" h2="On Premise Java API to Export ODS to POWERPOINT without relying on Microsoft Excel&reg;">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ODS to POWERPOINT Conversion on Java" %}}
1. Open ODS file using [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class
2. Convert ODS to PDF and set SaveFormat to AUTO
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class
4. Save the document to PPTX format using [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method and set Pptx as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java Total API" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project by following simple [installation](https://docs.aspose.com/words/java/installation/).

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code for ODS to POWERPOINT Conversion" gistPath="" %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}