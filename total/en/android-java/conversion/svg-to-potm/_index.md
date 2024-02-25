---
title: Export SVG to POTM in Android 
description: Android API to Convert SVG to POTM without using Microsoft Word
url_ignore: /android-java/conversion/svg-to-potm/
family: total
platformtag: android-java
feature: conversion
informat: SVG
outformat: POTM
otherformats: POT PPS PPT PPSX POTX SWF PPTM POWERPOINT OTP ODP XAML PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert SVG to POTM on Android via Java" h2="Transform SVG to POTM within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The Scalable Vector Graphics (SVG) format is a widely used vector image format that is used to create and display images on the web. It is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation. On the other hand, PowerPoint Open XML Macro-Enabled Presentation (POTM) is a file format used to store presentations created with Microsoft PowerPoint. It is a macro-enabled version of the PowerPoint Open XML Presentation (PPTX) file format.

<h2>How Aspose.Total helps for svg to potm conversion</h2>

Integrating SVG to POTM conversion feature inside your Android applications is now easy with Aspose.Total for Android via Java. It is a suite of file format APIs that enables developers to create, edit, render, print and convert between a wide range of popular document and image file formats. It includes Aspose.PDF for Android via Java and Aspose.Slides for Android via Java.

Aspose.PDF for Android via Java is a PDF document creation and manipulation component that enables developers to create, read, write and manipulate PDF documents without using Adobe Acrobat. It allows developers to export SVG to PPTX.

Aspose.Slides for Android via Java is a PowerPoint document manipulation component that enables developers to create, read, write and manipulate PowerPoint documents without using Microsoft PowerPoint. It allows developers to convert PPTX to POTM.

Both APIs come under Aspose.Total for Android via Java package. It is a suite of file format APIs that enables developers to create, edit, render, print and convert between a wide range of popular document and image file formats. It includes Aspose.PDF for Android via Java and Aspose.Slides for Android via Java.

Integrating SVG to POTM conversion feature inside your Android applications is now easy with Aspose.Total for Android via Java. It can be done in two simple steps. In the first step you can export SVG to PPTX by using Aspose.PDF for Android via Java. After that, by using Aspose.Slides for Android via Java, you can convert PPTX to POTM.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export SVG to POTM" %}}
1. Open SVG file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert SVG to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to POTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Potm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected SVG File in Android Apps" %}}
While loading SVG file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of POTM File in Android Applications" %}}
After converting SVG to POTM, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("output.potm");
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}