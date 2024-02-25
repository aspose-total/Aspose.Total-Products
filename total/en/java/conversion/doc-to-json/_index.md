---
title: Convert DOC to JSON Format via Java
description: Convert DOC to JSON format via Java without using using Microsoft Word or Microsoft Excel
url_ignore: /java/conversion/doc-to-json/
family: total
platformtag: java
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOC to JSON via Java" h2="On Premise Java API to convert DOC to JSON without using Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Why Convert Word DOC files to JSON?</h2>

Converting Word DOC files to JSON format is beneficial for extracting structured data and content from documents. This conversion streamlines data processing, enables content analysis, and facilitates integration with other systems, making it valuable for data extraction, data sharing, and document automation within various applications.

<h2 class="heading-border">How Aspose.Total can help in DOC to JSON Format Conversion?</h2>

[Aspose.Total for Java](https://products.aspose.com/total/java/) offers a quick and easy way to convert DOC to JSON format in any Java-based application. The conversion process is achieved in just two steps.

1. The first step involves using [Aspose.Words for Java](https://products.aspose.com/words/java/), a powerful document manipulation and conversion API, to export the DOC file to HTML format. This API allows you to programmatically create, modify, and convert a wide range of document formats including DOC, DOCX, PDF, and more. With Aspose.Words for Java, you can easily convert your DOC files to HTML format with just a few lines of code.
1. Once the DOC file has been converted to HTML, the second step is to use [Aspose.Cells for Java](https://products.aspose.com/cells/java/) to convert the HTML file to JSON format. Aspose.Cells for Java is a powerful spreadsheet programming API that allows you to create, modify, and convert Excel files in Java applications. It supports a wide range of Excel file formats, including XLS, XLSX, XLSM, and more. With Aspose.Cells for Java, you can easily convert HTML files to JSON format and manipulate the resulting data as needed.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOC to JSON via Java?" %}}
1. Load DOC file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOC to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tools Needed for DOC to JSON Conversion" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml. Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOC to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input DOC document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOC to JSON in Range via Java" %}}
While you are converting DOC to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}