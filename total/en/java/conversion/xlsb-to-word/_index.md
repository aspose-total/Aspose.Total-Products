---
title: Convert XLSB to WORD using Java 
description: Java API to Export XLSB to WORD with using Excel or Word 
url_ignore: /java/conversion/xlsb-to-word/
family: total
platformtag: java
feature: conversion
informat: XLSB
outformat: DOC
otherformats: DOCX POWERPOINT PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Java API to Export XLSB to WORD" h2="On Premise Java API to Export XLSB to WORD without relying on Microsoft Excel&reg;">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/pf/agp/content h2="How to Convert XLSB to WORD via Java API" isGrey="true" %}}
Rendering XLSB to WORD is a two step process. You’ll first use [Aspose.Cells for Java](https://products.aspose.com/cells/java) API to convert the given XLSB document to PDF, and then by using [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, you can easily convert your PDF document to WORD. Both APIs come under the collection of [Aspose.Total for Java](https://products.aspose.com/total/java/) file format automation libraries.
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB to WORD Conversion on Java" %}}
1. Open XLSB file using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
2. Convert XLSB to PDF and set SaveFormat to AUTO
3. Load the converted PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
4. Save the document to DOC format using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include [Aspose.Cells](https://docs.aspose.com/cells/java/installation/) and [Aspose.Pdf](https://docs.aspose.com/pdf/java/installation/#installing-asposepdf-for-java-from-aspose-repository) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code for XLSB to WORD Conversion" gistPath="" %}}
```cs// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}