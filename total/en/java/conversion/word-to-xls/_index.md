---
title: Convert WORD to XLS via Java
description: Convert WORD to XLS via Java without using using Microsoft Word or Microsoft Excel
url_ignore: /java/conversion/word-to-xls/
family: total
platformtag: java
feature: conversion
informat: DOC
outformat: XLS
otherformats: SXC CSV ODS XLSX EXCEL XLAM XLT XLSM XLTX TSV XLTM FODS XLSB XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert WORD to XLS via Java" h2="On Premise Java API to convert WORD to XLS without using Microsoft<sup>&reg;</sup> Word or Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
You can converting WORD to XLS via [Aspose.Total for Java](https://products.aspose.com/total/java/) is a simple two step process. By using feature-rich, document manipulation and conversion API [Aspose.Words for Java](https://products.aspose.com/words/java/), you can export WORD to HTML. After that, by using [Aspose.Cells for Java](https://products.aspose.com/cells/java/), you can convert HTML to XLS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert WORD to XLS via Java" %}}
1. Open WORD file using [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert WORD to HTML by using [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Load HTML document by using [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to XLS format using [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Automation APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected WORD to XLS via Java" %}}
Using the API, you can also open the password-protected document. If your input WORD document is password protected, you cannot convert it to XLS without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert WORD to Protected XLS file via Java" %}}
After you convert WORD to XLS, you can also encrypt and password protect your XLS documents. In order to encrypt your document, open it using Workbook class and specify XOR Encryption Type and Strong Encryption type (RC4, Microsoft Strong Cryptographic Provider) encryption by using the setEncryptionOptions method. You can also set a password to your XLS by using the Password property of WorkbookSettings class.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}