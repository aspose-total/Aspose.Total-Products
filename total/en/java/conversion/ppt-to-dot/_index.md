---
title: Convert PPT to DOT via Java
description: Java API to Export PPT to DOT without using Microsoft Word or PowerPoint
url_ignore: /java/conversion/ppt-to-dot/
family: total
platformtag: java
feature: conversion
informat: PPT
outformat: DOT
otherformats: WORDML DOTM RTF DOCM TEXT OTT DOTX FLATOPC WORD DOCX DOC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPT to DOT via Java" h2="On Premise Java API for PowerPoint PPT to DOT conversion within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) File Format Automation libraries empower Java developers to automate the batch conversion process of PowerPoint PPT to Word DOT. Converting the document is a two-step process and involves using two APIs. We’ll use [Aspose.Slides for Java](https://products.aspose.com/slides/java/) that is a PowerPoint API for presentations manipulation and management to convert PPT to HTML. After that by using feature-rich Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) we will convert the HTML to DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PPT to DOT via Java" %}}
1. Open PPT file using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert PPT to HTML by using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method and set Html as SaveFormat
3. Load the converted HTML file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
4. Save the document to DOT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PPT File Conversion in Java" %}}
For PPT to DOT file conversion, you can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected PPT to DOT via Java" %}}
The API also allows you to perform PPT to DOT conversion of password protected documents. If your input PPT document is password protected, you cannot convert it to DOT format without using the password. The API allows you to open the encrypted document by passing the correct password in a LoadOptions object.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-protected-powerpoint-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPT to DOT with Watermark via Java" %}}
Using the API, you can also perform PPT file to DOT conversion with watermark. In order to add a watermark to your DOT document, you can first convert the PPT  file to HTML and add a watermark to it. In order to add a watermark, load the newly created HTML file using the [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.setText method and pass watermark text & object of TextWatermarkOptions.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}