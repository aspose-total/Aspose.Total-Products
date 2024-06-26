---
title: Export PCL to PPTM in Android 
description: Android API to Convert PCL to PPTM without using Microsoft Word
url_ignore: /android-java/conversion/pcl-to-pptm/
family: total
platformtag: android-java
feature: conversion
informat: PCL
outformat: PPTM
otherformats: OTP POWERPOINT POTM PPSX POTX SWF XAML ODP PPS PPT PPSM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PCL to PPTM on Android via Java" h2="Transform PCL to PPTM within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The Portable Document Format (PDF) is a widely used file format for documents. It is used to store documents in a format that is independent of the application software, hardware, and operating system. However, the PDF format is not suitable for editing or presenting documents. Therefore, it is necessary to convert PDF documents to other formats such as Microsoft PowerPoint (PPT) or Microsoft PowerPoint Macro-Enabled Presentation (PPTM).

<h2>How Aspose.Total helps for PCL to PPTM Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to create, edit, and convert documents in various formats. It includes APIs for PDF, Slides, Words, Cells, and Barcode. By using Aspose.Total for Android via Java, you can easily integrate PCL to PPTM conversion feature inside your Android applications.

The process of converting PCL to PPTM involves two steps. In the first step, you can export PCL to PPTX by using Aspose.PDF for Android via Java. After that, by using Aspose.Slides for Android via Java, you can convert PPTX to PPTM. Both APIs come under Aspose.Total for Android via Java package.

The Aspose.PDF for Android via Java API provides a wide range of features to manipulate PDF documents. It enables you to convert PCL to PDF, extract text from PDF, add images to PDF, add watermarks to PDF, and much more.

The Aspose.Slides for Android via Java API provides a wide range of features to manipulate PowerPoint documents. It enables you to convert PPTX to PPTM, extract text from PPTM, add images to PPTM, add watermarks to PPTM, and much more.

By using Aspose.Total for Android via Java, you can easily integrate PCL to PPTM conversion feature inside your Android applications. It is a comprehensive suite of APIs that enables developers to create, edit, and convert documents in various formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export PCL to PPTM" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pptm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PCL File in Android Apps" %}}
While loading PCL file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPTM File in Android Applications" %}}
After converting PCL to PPTM, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
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