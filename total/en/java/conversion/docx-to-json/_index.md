---
title: Convert DOCX to JSON Format via Java
description: Export DOCX to JSON format via Java without using using Microsoft Word or Microsoft Excel
url_ignore: /java/conversion/docx-to-json/
family: total
platformtag: java
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCX to JSON Format via Java" h2="Export DOCX to JSON without using Microsoft<sup>&reg;</sup> Word, Microsoft<sup>&reg;</sup> Excel or any other application" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Why Convert DOCX to JSON format?</h2>

Exporting a DOCX file to JSON can be useful in several scenarios. One common use case is when working with large documents that contain a lot of structured data, such as tables, charts, and lists. By converting the DOCX file to JSON, the structured data can be easily extracted and manipulated using programming languages like Java, JavaScript, Python, and Ruby. Another reason why someone might want to export a DOCX file to JSON is to enable seamless integration with other software systems or platforms. JSON is a lightweight and widely supported data format that can be easily consumed by web applications, mobile apps, and other software tools. By converting the DOCX file to JSON, the data can be easily shared and integrated with other systems, making it more accessible and usable.

<h2 class="heading-border">How Aspose.Total can help in DOCX to JSON Conversion?</h2>

Converting DOCX to JSON format via [Aspose.Total for Java](https://products.aspose.com/total/java/) is a simple two step process. By using feature-rich, document manipulation and conversion API [Aspose.Words for Java](https://products.aspose.com/words/java/), you can export DOCX to HTML. After that, by using [Aspose.Cells for Java](https://products.aspose.com/cells/java/), you can convert HTML to JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOCX to JSON via Java?" %}}
1. Open DOCX file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOCX to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Word to JSON Converter Library for Java" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml. Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOCX to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input DOCX document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOCX to JSON in Range via Java" %}}
While you are converting DOCX to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}