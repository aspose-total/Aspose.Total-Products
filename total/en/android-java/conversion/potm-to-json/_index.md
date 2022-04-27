---
title: Convert POTM to JSON Format in Android via Java
description: Convert POTM to JSON format in Android via Java without using using Microsoft Excel or PowerPoint
url: /android-java/conversion/potm-to-json/
family: total
platformtag: android-java
feature: conversion
informat: POTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert POTM to JSON Format in Android via Java" h2="Export POTM file to JSON format in Android applications without using Microsoft<sup>&reg;</sup> Excel or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
You can easily convert POTM file to JSON format in you Android applications in a two step process via [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). In the first step you can export POTM file to HTML by using [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/). Secondly, by using [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), you can convert HTML to JSON format.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert POTM to JSON Format in Android" %}}
1. Open POTM file using [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert POTM to HTML by using [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method
3. Load HTML document by using [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class
4. Save the document to JSON format using [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Android via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) and install libraries in your app.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected POTM to JSON Format in Android" %}}
Using the API, you can also open the password-protected document. If your input POTM document is password protected, you cannot convert it to JSON format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object. The following code example shows how to try opening an encrypted document with a password:
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert POTM to JSON in Range in Android via Java" %}}
While you are converting POTM to JSON, you can also set range to your output JSON format. In order to set the range, you can open the converted HTML using Workbook class, create a Range of data to be exported using Cells.createRange method, call JsonUtility.exportRangeToJson method with references of Range & ExportRangeToJsonOptions and write string JSON data to file via BufferedWriter.write method.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}