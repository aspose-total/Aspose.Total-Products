---
title: Export XPS to PPTM in Android 
description: Android API to Convert XPS to PPTM without using Microsoft Word
url_ignore: /android-java/conversion/xps-to-pptm/
family: total
platformtag: android-java
feature: conversion
informat: XPS
outformat: PPTM
otherformats: POT PPSX OTP POWERPOINT PPT PPS ODP XAML POTM POTX SWF PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XPS to PPTM on Android via Java" h2="Transform XPS to PPTM within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to PPTM?</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft which is used to store documents in a fixed layout. It is similar to PDF format but it is not as popular as PDF. On the other hand, PPTM (PowerPoint Macro-Enabled Presentation) is a presentation format developed by Microsoft which is used to store presentations. It is a macro-enabled version of PPTX format and it is widely used for presentations. Therefore, it is necessary to convert XPS to PPTM in order to make the documents more accessible and compatible with other applications.

<h2>How Aspose.Total helps for XPS to PPTM Conversion?</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs which provides a wide range of features for document processing. It includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to convert XPS to PPTM. The first API can be used to export XPS to PPTX and the second API can be used to convert PPTX to PPTM. Both APIs come under the same package, Aspose.Total for Android via Java, which makes it easier to integrate the feature into Android applications. 

In order to integrate the XPS to PPTM conversion feature into Android applications, you need to follow two simple steps. In the first step, you need to export XPS to PPTX by using Aspose.PDF for Android via Java. After that, you need to convert PPTX to PPTM by using Aspose.Slides for Android via Java. Both APIs are available under the same package, Aspose.Total for Android via Java, which makes it easier to integrate the feature into Android applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export XPS to PPTM" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XPS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pptm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected XPS File in Android Apps" %}}
While loading XPS file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPTM File in Android Applications" %}}
After converting XPS to PPTM, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}