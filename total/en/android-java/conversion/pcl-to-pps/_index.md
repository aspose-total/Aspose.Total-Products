---
title: Export PCL to PPS in Android 
description: Android API to Convert PCL to PPS without using Microsoft Word
url_ignore: /android-java/conversion/pcl-to-pps/
family: total
platformtag: android-java
feature: conversion
informat: PCL
outformat: PPS
otherformats: POTM POT PPSX SWF PPT POTX PPSM ODP POWERPOINT OTP PPTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PCL to PPS on Android via Java" h2="Transform PCL to PPS within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

The Portable Document Format (PDF) is a popular file format used to store documents. It is widely used for sharing documents online and for printing. However, the PDF format is not suitable for editing. Therefore, it is necessary to convert PDF documents to other formats such as PowerPoint Presentation (PPT) or PowerPoint Show (PPS) for editing.

<h2>How Aspose.Total Helps for PCL to PPS Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to create, manipulate, convert, and render documents in various formats. It includes APIs for PDF, Slides, Words, Cells, and Barcode. With Aspose.Total, developers can easily integrate PCL to PPS conversion feature inside their Android applications.

The process of converting PCL to PPS involves two steps. In the first step, you can export PCL to PPTX by using Aspose.PDF for Android via Java. After that, you can convert PPTX to PPS by using Aspose.Slides for Android via Java. Both APIs come under Aspose.Total for Android via Java package.

The Aspose.PDF for Android via Java API provides a wide range of features for converting PCL to PPTX. It supports all versions of PCL and PPTX formats. It also allows developers to set various options such as page size, page orientation, and page margins. Moreover, it provides the ability to convert PCL to PPTX in a single line of code.

The Aspose.Slides for Android via Java API provides a wide range of features for converting PPTX to PPS. It supports all versions of PPTX and PPS formats. It also allows developers to set various options such as slide size, slide orientation, and slide margins. Moreover, it provides the ability to convert PPTX to PPS in a single line of code.

In conclusion, Aspose.Total for Android via Java is a comprehensive suite of APIs that enables developers to easily integrate PCL to PPS conversion feature inside their Android applications. It includes APIs for PDF and Slides, which can be used to export PCL to PPTX and convert PPTX to PPS respectively.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export PCL to PPS" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPS format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pps` as SaveFormat
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
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Password Protected PCL File in Android via Java" %}}
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of PPS File in Android Applications" %}}
After converting PCL to PPS, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("output.pps");
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