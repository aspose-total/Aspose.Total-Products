---
title: Export XPS to OTP in Android 
description: Android API to Convert XPS to OTP without using Microsoft Word
url_ignore: /android-java/conversion/xps-to-otp/
family: total
platformtag: android-java
feature: conversion
informat: XPS
outformat: OTP
otherformats: ODP POTX POWERPOINT PPS PPSM XAML PPTM SWF POTM POT PPT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XPS to OTP on Android via Java" h2="Transform XPS to OTP within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to OTP</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft. It is used to store documents in a fixed layout format. OTP (OpenDocument Presentation) is an open standard for electronic documents. It is used to store presentations in a format that is independent of the application software, hardware, and operating system. Converting XPS to OTP allows users to access the content of the XPS document in a format that is compatible with a variety of applications.

<h2>How Aspose.Total Helps for XPS to OTP Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to create, manipulate, and convert documents in a variety of formats. It includes two APIs that can be used to convert XPS to OTP: Aspose.PDF for Android via Java and Aspose.Slides for Android via Java. 

The first step in the conversion process is to export the XPS document to PPTX using Aspose.PDF for Android via Java. This API provides a set of features that allow developers to manipulate PDF documents, including the ability to convert PDF documents to other formats. After the XPS document has been exported to PPTX, Aspose.Slides for Android via Java can be used to convert the PPTX document to OTP. This API provides a set of features that allow developers to manipulate presentations, including the ability to convert presentations to other formats.

By using Aspose.Total for Android via Java, developers can easily integrate XPS to OTP conversion into their Android applications. The two APIs included in the suite provide all the features necessary to convert XPS documents to OTP, making the process quick and easy.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export XPS to OTP" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XPS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to OTP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Otp` as SaveFormat
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
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of OTP File in Android Applications" %}}
After converting XPS to OTP, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
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