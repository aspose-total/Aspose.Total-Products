---
title: Convert PPTM to JSON Format via Java
description: Convert PPTM to JSON format via Java without using using Microsoft Excel or PowerPoint
url_ignore: /java/conversion/pptm-to-json/
family: total
platformtag: java
feature: conversion
informat: PPTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPTM to JSON Format via Java" h2="On Premise Java API to export PPTM to JSON without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to easily convert PPTM to JSON format. This two-step process is simple and straightforward. 

The first step involves using Aspose.Slides for Java to export PPTM to HTML. This API provides a wide range of features for manipulating PowerPoint presentations. It enables developers to create, edit, and convert presentations to various formats. It also supports features such as adding text, shapes, images, and charts to presentations. 

The second step involves using Aspose.Cells for Java to convert HTML to JSON. This API provides a comprehensive set of features for working with spreadsheets. It enables developers to create, edit, and convert spreadsheets to various formats. It also supports features such as adding formulas, formatting cells, and applying conditional formatting. 

By using Aspose.Total for Java, developers can easily convert PPTM to JSON format. This two-step process is simple and straightforward. It enables developers to quickly and easily convert presentations to the desired format. Aspose.Total for Java is a comprehensive suite of APIs that provides developers with the tools they need to create, edit, and convert presentations and spreadsheets.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PPTM to JSON Format via Java" %}}
1. Open PPTM file using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert PPTM to HTML by using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPTM to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input PPTM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPTM to JSON in Range via Java" %}}
While you are converting PPTM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}