---
title: Convert PPT to JSON Format via Java
description: Convert PPT to JSON format via Java without using using Microsoft Excel or PowerPoint
url_ignore: /java/conversion/ppt-to-json/
family: total
platformtag: java
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPT to JSON Format via Java" h2="On Premise Java API to export PPT to JSON without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Using Aspose.Total for Java, converting a PowerPoint presentation (PPT) to JavaScript Object Notation (JSON) format is a straightforward two-step process. The first step involves exporting the PPT to HTML using Aspose.Slides for Java. This powerful library provides a wide range of features for creating, manipulating, and converting presentations. It also allows you to export presentations to HTML, which is the format required for the second step of the conversion process.

The second step involves using Aspose.Cells for Java to convert the HTML to JSON. This library provides a comprehensive set of features for working with spreadsheets, including the ability to convert HTML to JSON. It also supports a wide range of other formats, including XLSX, XLS, CSV, and ODS.

By using Aspose.Total for Java, you can quickly and easily convert PPT to JSON format. The two-step process is simple and straightforward, and the powerful features of Aspose.Slides and Aspose.Cells make it easy to export presentations to HTML and convert HTML to JSON.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PPT to JSON Format via Java" %}}
1. Open PPT file using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert PPT to HTML by using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPT to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input PPT document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to JSON in Range via Java" %}}
While you are converting PPT to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}