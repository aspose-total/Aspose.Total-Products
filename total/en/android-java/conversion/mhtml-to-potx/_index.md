---
title: Export MHTML to POTX in Android 
description: Android API to Convert MHTML to POTX without using Microsoft Word
url_ignore: /android-java/conversion/mhtml-to-potx/
family: total
platformtag: android-java
feature: conversion
informat: MHTML
outformat: POTX
otherformats: OTP PPS POWERPOINT POT PPSX PPTM SWF PPT XAML PPSM ODP POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MHTML to POTX on Android via Java" h2="Transform MHTML to POTX within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MHTML to POTX?</h2>

MHTML (MIME HTML) is a web page archive format that is used to save webpages for offline viewing. It is a combination of HTML code and resources such as images, audio, and video. On the other hand, POTX is a PowerPoint Open XML template file format used to store PowerPoint presentations. It is used to store the design of a presentation, including the background, fonts, colors, and effects. Converting MHTML to POTX allows users to create a template for a presentation that can be used multiple times.

<h2>How Aspose.Total Helps for MHTML to POTX Conversion?</h2>

Aspose.Total for Android via Java is a suite of APIs that helps developers to create, manipulate, and convert documents, images, and other file formats. It includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to convert MHTML to POTX. 

The first step is to export MHTML to PPTX by using Aspose.PDF for Android via Java. This API provides a wide range of features to convert MHTML to PPTX, including the ability to convert MHTML to PPTX with a single line of code. After that, Aspose.Slides for Android via Java can be used to convert PPTX to POTX. This API provides a range of features to convert PPTX to POTX, including the ability to convert PPTX to POTX with a single line of code. 

By using Aspose.Total for Android via Java, developers can easily integrate MHTML to POTX conversion feature inside their Android applications. It is a cost-effective solution that helps developers to save time and effort.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export MHTML to POTX" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MHTML to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to POTX format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Potx` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected MHTML File in Android via Java" %}}
While loading MHTML file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of POTX File in Android Applications" %}}
After converting MHTML to POTX, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("output.potx");
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