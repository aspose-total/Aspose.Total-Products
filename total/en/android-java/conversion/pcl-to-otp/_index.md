---
title: Export PCL to OTP in Android 
description: Android API to Convert PCL to OTP without using Microsoft Word
url_ignore: /android-java/conversion/pcl-to-otp/
family: total
platformtag: android-java
feature: conversion
informat: PCL
outformat: OTP
otherformats: PPT POTX POTM POT ODP PPS XAML POWERPOINT SWF PPSM PPSX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PCL to OTP on Android via Java" h2="Transform PCL to OTP within your Android Applications without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PCL to OTP</h2>

The Portable Document Format (PDF) is a widely used file format for documents. It is used to store documents in a format that is independent of the application used to create it. However, PDF files are not always suitable for editing or sharing. The OpenDocument Text (OTP) format is an open standard for document exchange that is supported by many applications. Converting PCL to OTP allows users to edit and share documents more easily.

<h2>How Aspose.Total Helps for PCL to OTP Conversion</h2>

Aspose.Total for Android via Java is a comprehensive suite of APIs that can be used to develop Android applications. It includes two APIs that can be used to convert PCL to OTP. The first API is Aspose.PDF for Android via Java, which can be used to export PCL to PPTX. The second API is Aspose.Slides for Android via Java, which can be used to convert PPTX to OTP. Both APIs come under the Aspose.Total for Android via Java package. 

To integrate PCL to OTP conversion feature inside an Android application, the user needs to follow two simple steps. In the first step, the user needs to export PCL to PPTX by using Aspose.PDF for Android via Java. After that, the user needs to use Aspose.Slides for Android via Java to convert PPTX to OTP. Both APIs are available under the Aspose.Total for Android via Java package. 

Aspose.Total for Android via Java is a comprehensive suite of APIs that can be used to develop Android applications. It includes two APIs that can be used to convert PCL to OTP. The first API is Aspose.PDF for Android via Java, which can be used to export PCL to PPTX. The second API is Aspose.Slides for Android via Java, which can be used to convert PPTX to OTP. Both APIs come under the Aspose.Total for Android via Java package. 

Using Aspose.Total for Android via Java, users can easily integrate PCL to OTP conversion feature inside their Android applications. The two APIs included in the package make it easy to export PCL to PPTX and then convert PPTX to OTP. This allows users to edit and share documents more easily.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API to Export PCL to OTP" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to OTP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Otp` as SaveFormat
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
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
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

{{% blocks/products/pf/feature-page-section  h2="Create Thumbnail Image of OTP File in Android Applications" %}}
After converting PCL to OTP, you can also create thumbnail images of your output document. By using rich in feature [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) you can generate thumbnail images of the slides by creating and instance of the [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class. After that, you can obtain the reference of any desired slide by using its ID or index and get the thumbnail image of the referenced slide on a specified scale.
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
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}