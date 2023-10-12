---
title: Export MHTML to PPT in Android 
description: Android API to Convert MHTML to PPT without using Microsoft Word
url_ignore: /android-java/conversion/mhtml-to-ppt/
family: total
platformtag: android-java
feature: conversion
informat: MHTML
outformat: PPT
otherformats: PPS PPTM ODP PPSM XAML OTP POTM POT POTX SWF PPSX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MHTML to PPT on Android via Java" h2="Transform MHTML to PPT within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MHTML to PPT</h2>

The MHTML format is a web page archive format that is used to save webpages in a single file. It is a combination of HTML and other resources such as images, audio, and video. It is used to save webpages for offline viewing. However, the MHTML format is not supported by many applications, including Microsoft PowerPoint. Therefore, it is necessary to convert MHTML to PPT in order to view the content in PowerPoint.

<h2>How Aspose.Total Helps for MHTML to PPT Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for PDF, Slides, and Words. With Aspose.Total, developers can easily integrate MHTML to PPT conversion feature inside their Android applications.

The process of converting MHTML to PPT involves two steps. In the first step, developers can export MHTML to PPTX by using Aspose.PDF for Android via Java. After that, they can convert PPTX to PPT by using Aspose.Slides for Android via Java. Both APIs come under Aspose.Total for Android via Java package.

The Aspose.PDF for Android via Java API provides a wide range of features for converting MHTML to PPTX. It supports various features such as text extraction, image extraction, page manipulation, and more. It also supports various file formats such as HTML, MHTML, XPS, and more.

The Aspose.Slides for Android via Java API provides a wide range of features for converting PPTX to PPT. It supports various features such as text extraction, image extraction, page manipulation, and more. It also supports various file formats such as PPT, PPTX, ODP, and more.

By using Aspose.Total for Android via Java, developers can easily integrate MHTML to PPT conversion feature inside their Android applications. It provides a simple and efficient way to convert MHTML to PPT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export MHTML to PPT" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MHTML to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPT format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppt` as SaveFormat
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
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected MHTML File in Android Apps" %}}
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPT File in Android Applications" %}}
After converting MHTML to PPT, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("output.ppt");
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