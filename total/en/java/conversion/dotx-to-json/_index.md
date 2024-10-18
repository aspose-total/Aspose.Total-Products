---
title: Convert DOTX to JSON Format via Java
description: Convert DOTX to JSON format via Java without using using Microsoft Word or Microsoft Excel
url_ignore: /java/conversion/dotx-to-json/
family: total
platformtag: java
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTX to JSON Format via Java" h2="On Premise Java API to convert DOTX to JSON without using Microsoft<sup>&reg;</sup> Word or Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


Using Aspose.Total for Java, converting DOTX to JSON format is a straightforward two-step process. Aspose.Total for Java is a comprehensive suite of feature-rich document manipulation and conversion APIs that enable developers to quickly and easily convert documents from one format to another. 

The first step is to export DOTX to HTML using Aspose.Words for Java. Aspose.Words for Java is a powerful document manipulation API that enables developers to create, edit, convert, and print documents in various formats, including DOTX. It provides a wide range of features, such as document creation, manipulation, and conversion, as well as support for a variety of document formats. With Aspose.Words for Java, developers can easily export DOTX to HTML. 

The second step is to convert HTML to JSON using Aspose.Cells for Java. Aspose.Cells for Java is a powerful spreadsheet manipulation API that enables developers to create, edit, and convert spreadsheets in various formats, including HTML. It provides a wide range of features, such as spreadsheet creation, manipulation, and conversion, as well as support for a variety of spreadsheet formats. With Aspose.Cells for Java, developers can easily convert HTML to JSON. 

By using Aspose.Total for Java, developers can quickly and easily convert DOTX to JSON format in just two steps. Aspose.Words for Java enables developers to export DOTX to HTML, and Aspose.Cells for Java enables developers to convert HTML to JSON. With Aspose.Total for Java, developers can easily manipulate and convert documents from one format to another.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOTX to JSON Format via Java" %}}
1. Open DOTX file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOTX to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java Conversion Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTX to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input DOTX document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTX to JSON in Range via Java" %}}
While you are converting DOTX to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}