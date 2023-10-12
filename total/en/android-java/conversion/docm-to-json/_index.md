---
title: Convert DOCM to JSON Format in Android Apps
description: Parse DOCM to JSON format in Android Apps without using Microsoft Word or Excel
url_ignore: /android-java/conversion/docm-to-json/
family: total
platformtag: android-java
feature: conversion
informat: DOCM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCM to JSON Format in Android Apps" h2="Design Android applications to export DOCM to JSON without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert DOCM to JSON?</h2>

The JSON (JavaScript Object Notation) format is a popular data interchange format used to store and exchange data. It is a lightweight, text-based, language-independent data format that is easy for humans to read and write. It is also easy for machines to parse and generate. JSON is often used in web applications to transfer data between a server and a client.

<h2>How Aspose.Total Helps for DOCM to JSON Conversion?</h2>

Aspose.Total for Android via Java is a comprehensive suite of document manipulation and conversion APIs that allow developers to easily convert DOCM to JSON format in their Android applications. Aspose.Words for Android via Java is a document manipulation API that enables developers to export DOCM to HTML. Aspose.Cells for Android via Java is a spreadsheet manipulation API that enables developers to convert HTML to JSON. With Aspose.Total, developers can quickly and easily convert DOCM to JSON format in their Android applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOCM to JSON Format in Android" %}}
1. Open DOCM file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOCM to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install libraries in your app.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOCM to JSON Format in Android Apps" %}}
Using the API, you can also open the password-protected document. If your input DOCM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how open an encrypted document with a password.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOCM to JSON in Range in Android Apps" %}}
While you are converting DOCM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}