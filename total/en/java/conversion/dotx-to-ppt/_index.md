---
title: Convert DOTX to PPT via Java
description: Java API to Export DOTX to PPT without using Microsoft Word or PowerPoint
url_ignore: /java/conversion/dotx-to-ppt/
family: total
platformtag: java
feature: conversion
informat: DOTX
outformat: PPT
otherformats: POTM ODP POT POTX PPTM POWERPOINT PPTX PPSX PPS PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTX to PPT via Java" h2="DOTX to PPT conversion by using on premise Java API within any Java J2SE, J2EE, J2ME applications without using Microsoft<sup>&reg;</sup> PowerPoint or Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Often times developers have to convert DOTX file to PPT programmatically. By using the File Automation Java libraries [Aspose.Total for Java](https://products.aspose.com/total/java/) you can automate the rendering process in a few simple steps. You can load your DOTX file by using [Aspose.Words for Java](https://products.aspose.com/words/java/) and convert it to HTML. After that by using powerful PowerPoint manipulation Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) you can create a new Presentation, write HTML content in it, and save it as PPT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOTX to PPT via Java" %}}
1. Open DOTX file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOTX file to HTML by using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Initialize a new [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) object
5. Extract content from HTML file using BufferedReader and write the content in your presentation file
6. Save the document to PPT using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="DOTX File Conversion in Java" %}}
For DOTX to PPT file conversion, you can easily use Aspose.Total for Java directly from a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTX to PPT via Java" %}}
The API also allows you to convert password-protected DOTX documents to PPT. If your input DOTX document is password protected, you cannot convert it to PPT format without using the password. In order to open a encrypted document you can set the correct password in LoadOptions object and pass it to the Document constructor. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTX to PPT with Watermark via Java" %}}
Using the API, you can also perform DOTX file to PPT conversion with watermark. In order to add a watermark to your PPT document, you can first export DOTX to HTML and write HTML content in [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) object. After that to add a watermark, you can add text using addTextFrame, set all the relevant options like color, fillType and more and can save the document to PPT.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}