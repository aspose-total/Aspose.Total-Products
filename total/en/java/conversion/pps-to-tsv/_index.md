---
title: Convert PPS to TSV Format via Java
description: Convert PPS to TSV format via Java without using using Microsoft Excel or PowerPoint
url: /java/conversion/pps-to-tsv/
family: total
platformtag: java
feature: conversion
informat: PPS
outformat: TSV
otherformats: XLAM XLS CSV MHTML DIF XLSX XLTX XLSB EXCEL XLTM MARKDOWN FODS XLT XLSM SXC ODS DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPS to TSV via Java" h2="On Premise Java API to export PPS to TSV without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
You can convert PPS file to TSV via [Aspose.Total for Java](https://products.aspose.com/total/java/) in two step steps. In the first step you can export PPS to HTML by using [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Secondly, by using [Aspose.Cells for Java](https://products.aspose.com/cells/java/), you can convert HTML to TSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PPS to TSV via Java" %}}
1. Open PPS file using [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert PPS to HTML by using [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method
3. Load HTML document by using [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to TSV format using [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PPS to TSV Conversion in Java" %}}
In order to convert PPS to TSV, you can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPS to TSV via Java" %}}
Using the API, you can also open the password-protected document. If your input PPS document is password protected, you cannot convert it to TSV without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPS File to TSV with Watermark via Java" %}}
While converting PPS file to TSV, you can also add watermark to your output TSV file format. In order to add a watermark, create a new Workbook to open the converted HTML file. Select Worksheet via its index, create a Shape and use its addTextEffect function, set colors, transparency and more. After that you can save your HTML document as TSV with Watermark.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}