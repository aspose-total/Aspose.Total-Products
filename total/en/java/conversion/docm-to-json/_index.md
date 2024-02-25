---
title: Convert DOCM to JSON Format via Java
description: Convert DOCM to JSON format via Java without using using Microsoft Word or Microsoft Excel
url_ignore: /java/conversion/docm-to-json/
family: total
platformtag: java
feature: conversion
informat: DOCM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCM to JSON Format via Java" h2="On Premise Java API to convert DOCM to JSON without using Microsoft<sup>&reg;</sup> Word or Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


Converting a DOCM file to JSON format can be easily accomplished with the help of Aspose.Total for Java. Aspose.Total for Java is a comprehensive suite of feature-rich APIs that enable developers to manipulate and convert documents with ease. The two-step process of converting a DOCM file to JSON format involves the use of Aspose.Words for Java and Aspose.Cells for Java.

Aspose.Words for Java is a powerful document manipulation and conversion API that enables developers to export DOCM files to HTML. This API provides a wide range of features such as document manipulation, document conversion, document comparison, document protection, and more. With the help of this API, developers can easily convert DOCM files to HTML with just a few lines of code.

Once the DOCM file is converted to HTML, Aspose.Cells for Java can be used to convert the HTML file to JSON format. Aspose.Cells for Java is a powerful spreadsheet manipulation and conversion API that enables developers to convert HTML files to JSON format with ease. This API provides a wide range of features such as spreadsheet manipulation, spreadsheet conversion, spreadsheet comparison, spreadsheet protection, and more. With the help of this API, developers can easily convert HTML files to JSON format with just a few lines of code.

In conclusion, converting a DOCM file to JSON format via Aspose.Total for Java is a simple two-step process. By using Aspose.Words for Java, developers can export DOCM files to HTML. After that, Aspose.Cells for Java can be used to convert the HTML file to JSON format. With the help of these two powerful APIs, developers can easily convert DOCM files to JSON format with just a few lines of code.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOCM to JSON Format via Java" %}}
1. Open DOCM file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOCM to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOCM to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input DOCM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOCM to JSON in Range via Java" %}}
While you are converting DOCM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}