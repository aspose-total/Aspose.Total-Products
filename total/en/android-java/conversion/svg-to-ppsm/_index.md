---
title: Export SVG to PPSM in Android 
description: Android API to Convert SVG to PPSM without using Microsoft Word
url_ignore: /android-java/conversion/svg-to-ppsm/
family: total
platformtag: android-java
feature: conversion
informat: SVG
outformat: PPSM
otherformats: XAML POT PPS PPT POTX ODP SWF OTP POTM PPTM PPSX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert SVG to PPSM on Android via Java" h2="Transform SVG to PPSM within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

SVG (Scalable Vector Graphics) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation. It is widely used for web graphics, and can also be used for print graphics. On the other hand, PPSM (PowerPoint Slide Show) is a presentation format used by Microsoft PowerPoint. It is used to store slides in a single file, which can be used for sharing and viewing presentations. Therefore, it is necessary to convert SVG to PPSM in order to view and share SVG images in a presentation format.

<h2>How Aspose.Total helps for SVG to PPSM Conversion</h2>

Aspose.Total for Android via Java is a comprehensive package of APIs that provides a wide range of features for developing Android applications. It includes Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to convert SVG to PPSM.

In order to integrate SVG to PPSM conversion feature inside your Android applications, you can follow two simple steps. First, you can export SVG to PPTX by using Aspose.PDF for Android via Java. After that, you can convert PPTX to PPSM by using Aspose.Slides for Android via Java. Both APIs come under Aspose.Total for Android via Java package.

Aspose.PDF for Android via Java provides a wide range of features for manipulating PDF documents. It allows you to export SVG to PPTX, which can be used as an intermediate format for converting SVG to PPSM.

Aspose.Slides for Android via Java provides a wide range of features for manipulating PowerPoint presentations. It allows you to convert PPTX to PPSM, which can be used for sharing and viewing presentations.

Therefore, Aspose.Total for Android via Java provides a comprehensive solution for integrating SVG to PPSM conversion feature inside your Android applications. It includes Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export SVG to PPTX and convert PPTX to PPSM respectively.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export SVG to PPSM" %}}
1. Open SVG file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert SVG to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsm` as SaveFormat
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
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPSM File in Android Applications" %}}
After converting SVG to PPSM, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("output.ppsm");
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