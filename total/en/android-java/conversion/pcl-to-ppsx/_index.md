---
title: Export PCL to PPSX in Android 
description: Android API to Convert PCL to PPSX without using Microsoft Word
url_ignore: /android-java/conversion/pcl-to-ppsx/
family: total
platformtag: android-java
feature: conversion
informat: PCL
outformat: PPSX
otherformats: POTM PPSM XAML SWF PPTM POTX ODP PPS OTP POT PPT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PCL to PPSX on Android via Java" h2="Transform PCL to PPSX within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The Portable Document Format (PDF) is a widely used file format for documents. It is a popular choice for sharing documents due to its compatibility with different operating systems and devices. However, PDF files are not suitable for editing. To make changes to a PDF document, it needs to be converted to a different format. One of the most popular formats for editing documents is the PowerPoint Presentation (PPSX) format.

<h2>How Aspose.Total Helps for PCL to PPSX Conversion</h2>

Integrating PCL to PPSX conversion feature inside Android applications is now possible with Aspose.Total for Android via Java. This package includes two APIs, Aspose.PDF for Android via Java and Aspose.Slides for Android via Java, which can be used to export PCL to PPTX and then convert PPTX to PPSX respectively. 

The first step is to export PCL to PPTX by using Aspose.PDF for Android via Java. This API provides a wide range of features for manipulating PDF documents. It can be used to convert PDF documents to other formats such as PPTX, XLSX, HTML, and more. It also supports features such as document splitting, merging, text extraction, and more.

The second step is to convert PPTX to PPSX by using Aspose.Slides for Android via Java. This API provides a wide range of features for manipulating PowerPoint presentations. It can be used to convert PPTX documents to other formats such as PPSX, PDF, HTML, and more. It also supports features such as document splitting, merging, text extraction, and more.

By using Aspose.Total for Android via Java, developers can easily integrate PCL to PPSX conversion feature inside their Android applications. This package provides a comprehensive set of APIs for manipulating documents and presentations, making it an ideal choice for developers who need to integrate document and presentation processing features into their applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export PCL to PPSX" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSX format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsx` as SaveFormat
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
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPSX File in Android Applications" %}}
After converting PCL to PPSX, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("output.ppsx");
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