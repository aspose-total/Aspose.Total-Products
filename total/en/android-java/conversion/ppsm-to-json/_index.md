---
title: Convert PPSM to JSON Format in Android via Java
description: Convert PPSM to JSON format in Android via Java without using using Microsoft Excel or PowerPoint
url_ignore: /android-java/conversion/ppsm-to-json/
family: total
platformtag: android-java
feature: conversion
informat: PPSM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPSM to JSON Format in Android via Java" h2="Export PPSM file to JSON format in Android applications without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The Portable Presentation Slide Show (PPSM) format is a file format used to store presentations created with Microsoft PowerPoint. It is a binary file format that is not easily readable by humans. JSON (JavaScript Object Notation) is a lightweight data-interchange format that is easy for humans to read and write. It is an open standard format that is used to transmit data objects consisting of attribute–value pairs and array data types. Converting PPSM to JSON makes it easier to read and manipulate the data.

<h2>How Aspose.Total Helps for PPSM to JSON Conversion</h2>

Aspose.Total for Android via Java is a suite of file format APIs that enables developers to easily convert PPSM file to JSON format in Android applications. It consists of three components: Aspose.Slides for Android via Java, Aspose.Cells for Android via Java, and Aspose.Words for Android via Java. 

The first step in the conversion process is to export the PPSM file to HTML using Aspose.Slides for Android via Java. This API provides a wide range of features for creating, manipulating, and converting presentations. It enables developers to export presentations to HTML format with just a few lines of code.

The second step is to convert the HTML file to JSON format using Aspose.Cells for Android via Java. This API provides a wide range of features for creating, manipulating, and converting spreadsheets. It enables developers to convert HTML files to JSON format with just a few lines of code.

With Aspose.Total for Android via Java, developers can easily convert PPSM files to JSON format in Android applications in a two-step process. It provides a comprehensive suite of APIs for creating, manipulating, and converting a wide range of file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PPSM to JSON Format in Android" %}}
1. Open PPSM file using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert PPSM to HTML by using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method
3. Load HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install libraries in your app.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPSM to JSON Format in Android" %}}
Using the API, you can also open the password-protected document. If your input PPSM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSM to JSON in Range in Android via Java" %}}
While you are converting PPSM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}