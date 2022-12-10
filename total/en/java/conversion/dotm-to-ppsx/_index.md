---
title: Convert DOTM to PPSX via Java
description: Java API to Export DOTM to PPSX without using Microsoft Word or PowerPoint
url_ignore: /java/conversion/dotm-to-ppsx/
family: total
platformtag: java
feature: conversion
informat: DOTM
outformat: PPSX
otherformats: PPSM PPS ODP POTM POWERPOINT PPT PPTM POTX PPTX POT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTM to PPSX via Java" h2="DOTM to PPSX conversion by using on premise Java API within any Java J2SE, J2EE, J2ME applications without using Microsoft<sup>&reg;</sup> PowerPoint or Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Often times developers have to convert DOTM file to PPSX programmatically. By using the File Automation Java libraries [Aspose.Total for Java](https://products.aspose.com/total/java/) you can automate the rendering process in a few simple steps. You can load your DOTM file by using [Aspose.Words for Java](https://products.aspose.com/words/java/) and convert it to HTML. After that by using powerful PowerPoint manipulation Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) you can create a new Presentation, write HTML content in it, and save it as PPSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOTM to PPSX via Java" %}}
1. Open DOTM file using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class
2. Convert DOTM file to HTML by using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method
3. Initialize a new [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) object
5. Extract content from HTML file using BufferedReader and write the content in your presentation file
6. Save the document to PPSX using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="DOTM File Conversion in Java" %}}
For DOTM to PPSX file conversion, you can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include libraries in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Protected DOTM to PPSX via Java" %}}
The API also allows you to convert password-protected DOTM documents to PPSX. If your input DOTM document is password protected, you cannot convert it to PPSX format without using the password. In order to open a encrypted document you can set the correct password in LoadOptions object and pass it to the Document constructor. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert DOTM to PPSX with Watermark via Java" %}}
Using the API, you can also perform DOTM file to PPSX conversion with watermark. In order to add a watermark to your PPSX document, you can first export DOTM to HTML and write HTML content in [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) object. After that to add a watermark, you can add text using addTextFrame, set all the relevant options like color, fillType and more and can save the document to PPSX.
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}