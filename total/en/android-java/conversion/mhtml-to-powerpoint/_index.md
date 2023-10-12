---
title: Export MHTML to POWERPOINT in Android 
description: Android API to Convert MHTML to POWERPOINT without using Microsoft Word
url_ignore: /android-java/conversion/mhtml-to-powerpoint/
family: total
platformtag: android-java
feature: conversion
informat: MHTML
outformat: PPT
otherformats: ODP OTP POT POTX PPSM POTM PPS PPSX XAML PPTM SWF PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MHTML to POWERPOINT on Android via Java" h2="Transform MHTML to POWERPOINT within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MHTML to PowerPoint?</h2>

MHTML (MIME HTML) is a web page archive format that combines resources such as images, audio, and video into a single file. It is used to save webpages for offline viewing and is supported by most web browsers. On the other hand, PowerPoint is a popular presentation software developed by Microsoft. It is used to create slideshows and presentations, and is widely used in business and educational settings. Converting MHTML to PowerPoint allows users to view webpages offline and share them with others in a more organized and professional manner.

<h2>How Aspose.Total Helps for MHTML to PowerPoint Conversion?</h2>

Integrating MHTML to PowerPoint conversion feature inside Android applications is now possible with Aspose.Total for Android via Java. This package includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export MHTML to PPTX and then convert PPTX to PowerPoint, respectively. 

The first step is to export MHTML to PPTX by using Aspose.PDF for Android via Java. This API provides a wide range of features for manipulating PDF documents, including the ability to convert MHTML to PPTX. After that, Aspose.Slides for Android via Java can be used to convert PPTX to PowerPoint. This API provides a comprehensive set of features for creating, manipulating, and converting presentations.

By using Aspose.Total for Android via Java, developers can easily integrate MHTML to PowerPoint conversion feature inside their Android applications. This package provides a comprehensive set of features for manipulating PDF documents and presentations, making it an ideal choice for developers who need to convert MHTML to PowerPoint.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export MHTML to POWERPOINT" %}}
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of POWERPOINT File in Android Applications" %}}
After converting MHTML to POWERPOINT, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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