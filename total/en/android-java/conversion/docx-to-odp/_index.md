---
title: Convert DOCX to ODP in Android via Java
description: DOCX to ODP conversion in your Android Phones without using Microsoft Word of PowerPoint 
url_ignore: /android-java/conversion/docx-to-odp/
family: total
platformtag: android-java
feature: conversion
informat: DOCX
outformat: ODP
otherformats: PPS POWERPOINT PPTX PPSM PPTM POTM POTX PPT POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCX to ODP in Android Apps" h2="DOCX to ODP conversion in your Android Applications without installing Microsoft Word<sup>&reg;</sup> or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Are you an Android developer looking to add a document conversion feature to your application? [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation libraries can help you automate the document conversion process in your Android applications. In order to convert DOCX file to ODP, you can first use document manipulation API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) to convert DOCX file format to HTML. After that by using PowerPoint API [Aspose.Slides for Android Java](https://products.aspose.com/slides/android-java/), you can create a new Presentation, write HTML content in it, and save it as ODP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOCX to ODP in Android" %}}
1. Open DOCX file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOCX file to HTML by using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Initialize a new [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) object
5. Extract content from HTML file using BufferedReader and write the content in your presentation file
6. Save the document to ODP using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="DOCX File Conversion in Android" %}}
For DOCX to ODP file conversion, you can easily use Aspose.Total for Android via Java directly from [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) and install libraries in your app.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOCX to ODP in Android via Java" %}}
You can also convert your password-protected DOCX to ODP within your Android applications. If your input DOCX document is password protected, you cannot convert it to ODP format without using the password. In order to open an encrypted document, you can set the correct password in the LoadOptions object and pass it to the Document constructor. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOCX to ODP with Watermark in Android via Java" %}}
Within your Android applications, the API also allows you to perform DOCX file to ODP conversion with watermark. 
In order to add a watermark to your ODP document, you can first export DOCX to HTML and write HTML content in [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) object. After that to add a watermark, you can add text using addTextFrame, set all the relevant options like color, fillType and more and can save the document to ODP.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}