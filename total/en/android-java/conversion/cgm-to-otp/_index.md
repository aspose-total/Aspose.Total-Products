---
title: Export CGM to OTP in Android 
description: Android API to Convert CGM to OTP without using Microsoft Word
url_ignore: /android-java/conversion/cgm-to-otp/
family: total
platformtag: android-java
feature: conversion
informat: CGM
outformat: OTP
otherformats: POTX PPSM PPTM POT SWF PPSX POTM PPS XAML ODP POWERPOINT PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert CGM to OTP on Android via Java" h2="Transform CGM to OTP within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The CGM (Computer Graphics Metafile) format is a vector-based graphics format that is used to store and exchange graphics data. It is widely used in the engineering and technical fields, and is also used in the printing industry. However, the OTP (OpenType Font) format is a more modern and widely used format for storing and exchanging text and graphics data. Therefore, it is often necessary to convert CGM to OTP in order to make the data more accessible and easier to use.

<h2>How Aspose.Total Helps for CGM to OTP Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to easily integrate CGM to OTP conversion feature into their Android applications. The suite includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export CGM to PPTX and then convert PPTX to OTP, respectively. 

The Aspose.PDF for Android via Java API provides a set of classes and methods that allow developers to easily create, read, modify, and convert PDF documents. It also supports the export of CGM to PPTX format. The Aspose.Slides for Android via Java API provides a set of classes and methods that allow developers to create, read, modify, and convert presentations. It also supports the conversion of PPTX to OTP format. 

By using these two APIs, developers can easily integrate CGM to OTP conversion feature into their Android applications. The APIs are easy to use and provide a wide range of features that make it easy to create, read, modify, and convert documents and presentations. Furthermore, the APIs are highly reliable and provide excellent performance.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export CGM to OTP" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert CGM to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to OTP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Otp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) and [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected CGM File in Android Apps" %}}
While loading CGM file format, your document might be password protected. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of OTP File in Android Applications" %}}
After converting CGM to OTP, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("output.otp");
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