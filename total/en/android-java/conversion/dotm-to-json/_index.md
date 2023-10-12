---
title: Convert DOTM to JSON Format in Android Apps
description: Parse DOTM to JSON format in Android Apps without using Microsoft Word or Excel
url_ignore: /android-java/conversion/dotm-to-json/
family: total
platformtag: android-java
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTM to JSON Format in Android Apps" h2="Design Android applications to export DOTM to JSON without using Microsoft<sup>&reg;</sup> Word or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The DOTM format is a Microsoft Office Word template file used to create documents with a consistent look and feel. It is a great way to ensure that all documents created with the same template have the same formatting, layout, and design. However, the DOTM format is not compatible with many other applications, making it difficult to share documents with other users. Converting DOTM to JSON format can make it easier to share documents with other users, as JSON is a widely used format that is supported by many applications.

<h2>How Aspose.Total Helps for DOTM to JSON Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of document manipulation and conversion APIs that can be used to convert DOTM to JSON format. It includes the Aspose.Words for Android via Java API, which can be used to export DOTM to HTML. The Aspose.Cells for Android via Java API can then be used to convert the HTML to JSON. This makes it easy to convert DOTM to JSON format in your Android applications. Aspose.Total for Android via Java also includes other APIs that can be used to manipulate and convert other document formats, making it a powerful and versatile tool for document manipulation and conversion.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOTM to JSON Format in Android" %}}
1. Open DOTM file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOTM to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
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

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTM to JSON Format in Android Apps" %}}
Using the API, you can also open the password-protected document. If your input DOTM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how open an encrypted document with a password.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTM to JSON in Range in Android Apps" %}}
While you are converting DOTM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}