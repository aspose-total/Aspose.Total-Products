---
title: Export PDF to ODP in Android 
description: Android API to Convert PDF to ODP without using Microsoft Word
url_ignore: /android-java/conversion/pdf-to-odp/
family: total
platformtag: android-java
feature: conversion
informat: PDF
outformat: ODP
otherformats: XAML POT PPSM OTP PPSX PPS POWERPOINT PPTM PPT SWF POTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to ODP on Android via Java" h2="Transform PDF to ODP within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PDF to ODP?</h2>

The OpenDocument Presentation (ODP) format is an open standard for electronic presentations created by the OpenDocument Format for Office Applications (ODF). It is used for creating presentations, slideshows, and other documents that can be shared across multiple platforms. ODP files are compatible with a variety of software programs, including Microsoft PowerPoint, OpenOffice, and LibreOffice.

<h2>How Aspose.Total Helps for PDF to ODP Conversion?</h2>

Integrating PDF to ODP conversion feature inside Android applications is now possible with two simple steps. Aspose.Total for Android via Java package provides two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export PDF to PPTX and then convert PPTX to ODP. 

In the first step, Aspose.PDF for Android via Java can be used to export PDF to PPTX. This API provides a wide range of features to manipulate PDF documents, such as creating, editing, converting, and printing PDF documents. It also supports a variety of image formats, including JPG, PNG, TIFF, and BMP.

In the second step, Aspose.Slides for Android via Java can be used to convert PPTX to ODP. This API provides a wide range of features to manipulate presentations, such as creating, editing, converting, and printing presentations. It also supports a variety of image formats, including JPG, PNG, TIFF, and BMP.

By using Aspose.Total for Android via Java package, developers can easily integrate PDF to ODP conversion feature inside their Android applications. This package provides two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export PDF to PPTX and then convert PPTX to ODP.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export PDF to ODP" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to ODP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Odp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PDF File in Android via Java" %}}
While loading PDF file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of ODP File in Android Applications" %}}
After converting PDF to ODP, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("output.odp");
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