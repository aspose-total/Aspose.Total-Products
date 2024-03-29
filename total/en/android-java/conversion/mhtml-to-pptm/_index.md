---
title: Export MHTML to PPTM in Android 
description: Android API to Convert MHTML to PPTM without using Microsoft Word
url_ignore: /android-java/conversion/mhtml-to-pptm/
family: total
platformtag: android-java
feature: conversion
informat: MHTML
outformat: PPTM
otherformats: ODP POTM OTP POWERPOINT XAML PPSX PPT PPS SWF PPSM POT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert MHTML to PPTM on Android via Java" h2="Transform MHTML to PPTM within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MHTML to PPTM?</h2>

MHTML (MIME HTML) is a web page archive format that is used to save web pages for offline viewing. It is a combination of HTML code and resources such as images, audio, and video. On the other hand, PPTM is a presentation file format used by Microsoft PowerPoint. It is a macro-enabled version of the PPTX file format. Converting MHTML to PPTM allows users to view the web page content in a presentation format.

<h2>How Aspose.Total Helps for MHTML to PPTM Conversion?</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to create, manipulate, convert, and render documents, images, and other file formats. It includes Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to convert MHTML to PPTM.

In order to integrate MHTML to PPTM conversion feature inside your Android applications, you can follow two simple steps. First, you can export MHTML to PPTX by using Aspose.PDF for Android via Java. After that, you can convert PPTX to PPTM by using Aspose.Slides for Android via Java. Both APIs come under Aspose.Total for Android via Java package.

Aspose.PDF for Android via Java provides a wide range of features to manipulate PDF documents. It allows you to convert MHTML to PPTX with ease. It also supports a variety of other file formats such as HTML, XPS, PCL, EPUB, and many more.

Aspose.Slides for Android via Java is a powerful API that enables developers to create, manipulate, and convert presentations. It allows you to convert PPTX to PPTM with ease. It also supports a variety of other file formats such as PPT, PPS, POT, ODP, and many more.

By using Aspose.Total for Android via Java, you can easily integrate MHTML to PPTM conversion feature inside your Android applications. It provides a comprehensive set of APIs to manipulate documents, images, and other file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export MHTML to PPTM" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MHTML to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pptm` as SaveFormat
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
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPTM File in Android Applications" %}}
After converting MHTML to PPTM, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
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