---
title: Convert PPSM to RTF via Java
description: Java API to Export PPSM to RTF without using Microsoft Word or PowerPoint
url_ignore: /java/conversion/ppsm-to-rtf/
family: total
platformtag: java
feature: conversion
informat: PPSM
outformat: RTF
otherformats: DOCX DOCM TEXT OTT WORDML DOTX WORD DOC ODT FLATOPC DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPSM to RTF via Java" h2="On Premise Java API for PowerPoint PPSM to RTF conversion within any Java J2SE, J2EE, J2ME applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) File Format Automation libraries empower Java developers to automate the batch conversion process of PowerPoint PPSM to Word RTF. Converting the document is a two-step process and involves using two APIs. We’ll use [Aspose.Slides for Java](https://products.aspose.com/slides/java/) that is a PowerPoint API for presentations manipulation and management to convert PPSM to HTML. After that by using feature-rich Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) we will convert the HTML to RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PPSM to RTF via Java" %}}
1. Open PPSM file using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class
2. Convert PPSM to HTML by using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method and set Html as SaveFormat
3. Load the converted HTML file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
4. Save the document to RTF format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PPSM File Conversion in Java" %}}
For PPSM to RTF file conversion, you can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PPSM to RTF with Watermark via Java" %}}
Using the API, you can also perform PPSM file to RTF conversion with watermark. In order to add a watermark to your RTF document, you can first convert the PPSM  file to HTML and add a watermark to it. In order to add a watermark, load the newly created HTML file using the [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class, create an instance of TextWatermarkOptions and set its properties, Call Watermark.setText method and pass watermark text & object of TextWatermarkOptions.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}