---
title: Export XSLFO to PPTM in Android 
description: Android API to Convert XSLFO to PPTM without using Microsoft Word
url_ignore: /android-java/conversion/xslfo-to-pptm/
family: total
platformtag: android-java
feature: conversion
informat: XSLFO
outformat: PPTM
otherformats: POT PPSX XAML PPS POTM ODP OTP POWERPOINT POTX PPT PPSM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XSLFO to PPTM on Android via Java" h2="Transform XSLFO to PPTM within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XSLFO to PPTM</h2>

XSLFO (XSL Formatting Objects) is a markup language for XML document formatting which is used to define the layout of a document. It is used to define the structure of a document, such as page size, margins, fonts, and other formatting information. On the other hand, PPTM (PowerPoint Macro-Enabled Presentation) is a presentation file format used by Microsoft PowerPoint. It is similar to PPTX, but it supports macros and ActiveX controls. Therefore, it is necessary to convert XSLFO to PPTM in order to make the document compatible with Microsoft PowerPoint.

<h2>How Aspose.Total helps for XSLFO to PPTM Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to create, manipulate, convert, and render documents, images, and other file formats. It includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to convert XSLFO to PPTM. 

The first step is to export XSLFO to PPTX by using Aspose.PDF for Android via Java. This API provides a wide range of features to manipulate PDF documents, such as creating, editing, converting, and rendering PDF documents. It also supports the conversion of XSLFO to PPTX.

The second step is to convert PPTX to PPTM by using Aspose.Slides for Android via Java. This API provides a wide range of features to manipulate PowerPoint presentations, such as creating, editing, converting, and rendering presentations. It also supports the conversion of PPTX to PPTM.

Therefore, by using Aspose.Total for Android via Java, developers can easily integrate XSLFO to PPTM conversion feature inside their Android applications in just two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export XSLFO to PPTM" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XSLFO to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pptm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected XSLFO File in Android Apps" %}}
While loading XSLFO file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPTM File in Android Applications" %}}
After converting XSLFO to PPTM, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("output.pptm");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}