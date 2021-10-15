---
title: Convert XLTX to DOCX using Java 
description: Java API to Export XLTX to DOCX with using Excel or Word 
url: /java/conversion/xltx-to-docx/
family: total
platformtag: java
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: PPTX WORD DOC POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Java API to Export XLTX to DOCX" h2="On Premise Java API to Export XLTX to DOCX without relying on Microsoft Excel&reg;">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/pf/agp/content h2="How to Convert XLTX to DOCX via Java API" isGrey="true" %}}
Rendering XLTX to DOCX is a two step process. You’ll first use [Aspose.Cells for Java](https://products.aspose.com/cells/java) API to convert the given XLTX document to PDF, and then by using [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, you can easily convert your PDF document to DOCX. Both APIs come under the collection of [Aspose.Total for Java](https://products.aspose.com/total/java/) file format automation libraries.
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/feature-section-col title="XLTX to DOCX Conversion on Java" %}}
1. Open XLTX file using [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class
2. Convert XLTX to PDF and set SaveFormat to AUTO
3. Load the converted PDF file using [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) class
4. Save the document to DOCX format using [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method and set DocX as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include [Aspose.Cells](https://docs.aspose.com/cells/java/installation/) and [Aspose.Pdf](https://docs.aspose.com/pdf/java/installation/#installing-asposepdf-for-java-from-aspose-repository) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code for XLTX to DOCX Conversion" gistPath="" %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocX);  
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}