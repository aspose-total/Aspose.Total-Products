---
title: Convert DOTM to JSON Format via Java
description: Convert DOTM to JSON format via Java without using using Microsoft Word or Microsoft Excel
url_ignore: /java/conversion/dotm-to-json/
family: total
platformtag: java
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTM to JSON Format via Java" h2="On Premise Java API to convert DOTM to JSON without using Microsoft<sup>&reg;</sup> Word or Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}


Using Aspose.Total for Java, converting DOTM to JSON format is a straightforward two-step process. First, you can use the feature-rich document manipulation and conversion API Aspose.Words for Java to export DOTM to HTML. Then, you can use Aspose.Cells for Java to convert the HTML to JSON.

Aspose.Total for Java is a comprehensive suite of APIs that provides developers with the tools they need to create, manipulate, and convert documents, spreadsheets, and presentations. Aspose.Words for Java is a powerful API that enables developers to create, edit, and convert documents in a variety of formats, including DOTM. It also provides features such as document manipulation, mail merge, and document comparison. Aspose.Cells for Java is a powerful API that enables developers to create, edit, and convert spreadsheets in a variety of formats, including HTML. It also provides features such as data validation, charting, and pivot tables.

Using Aspose.Total for Java, you can quickly and easily convert DOTM to JSON format. First, you can use Aspose.Words for Java to export DOTM to HTML. Then, you can use Aspose.Cells for Java to convert the HTML to JSON. This two-step process is simple and efficient, and it allows you to quickly and easily convert DOTM to JSON format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert DOTM to JSON Format via Java" %}}
1. Open DOTM file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOTM to HTML by using [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTM to JSON Format via Java" %}}
Using the API, you can also open the password-protected document. If your input DOTM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTM to JSON in Range via Java" %}}
While you are converting DOTM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}