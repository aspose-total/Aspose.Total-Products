---
title: Export PDF to SWF in Android 
description: Android API to Convert PDF to SWF without using Microsoft Word
url_ignore: /android-java/conversion/pdf-to-swf/
family: total
platformtag: android-java
feature: conversion
informat: PDF
outformat: SWF
otherformats: POTX XAML OTP PPT PPSM PPS PPTM ODP PPSX POWERPOINT POTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to SWF on Android via Java" h2="Transform PDF to SWF within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PDF to SWF</h2>

PDF to SWF conversion is a useful process for Android application developers. SWF is a file format used for displaying vector graphics, audio, and video on the web. It is a popular format for displaying interactive content, such as animations, games, and presentations. Converting PDF to SWF allows developers to create interactive content that can be easily shared and viewed on the web.

<h2>How Aspose.Total Helps for PDF to SWF Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to easily integrate PDF to SWF conversion into their Android applications. The package includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export PDF to PPTX and then convert PPTX to SWF. Both APIs are easy to use and provide a wide range of features to help developers create high-quality, interactive content. 

To use the APIs, developers first need to install the Aspose.Total for Android via Java package. Once the package is installed, developers can use the Aspose.PDF for Android via Java API to export PDF to PPTX. This API provides a range of features, such as the ability to convert PDF to other formats, extract text from PDF documents, and add annotations to PDF files. 

After exporting PDF to PPTX, developers can use the Aspose.Slides for Android via Java API to convert PPTX to SWF. This API provides a range of features, such as the ability to create, edit, and convert presentations, add animations and transitions, and embed audio and video. With these features, developers can easily create high-quality, interactive content that can be shared and viewed on the web. 

By using Aspose.Total for Android via Java, developers can easily integrate PDF to SWF conversion into their Android applications. The package includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export PDF to PPTX and then convert PPTX to SWF. With these APIs, developers can create high-quality, interactive content that can be easily shared and viewed on the web.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export PDF to SWF" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PDF to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to SWF format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Swf` as SaveFormat
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
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of SWF File in Android Applications" %}}
After converting PDF to SWF, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a SWF file
Presentation presentation = new Presentation("output.swf");
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