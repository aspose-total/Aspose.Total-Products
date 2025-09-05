---
title: Online XPS to ODP Conversion or Develop Java based Application to Convert XPS Files
description: Free online app to convert XPS to ODP files. Java conversion library code for XPS documents. 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: ODP
otherformats: POTM PPT PPS POT SWF PPSM PPTM OTP POWERPOINT PPSX POTX XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Online XPS to ODP Conversion App and Java Code to Convert XPS Files" h2="Develop powerful Java based XPS conversion and exporting application. Convert single or multiple XPS files to ODP and other formats via Java automation API. Freely convert XPS files online via app with instant download." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Free Online XPS to ODP Conversion App" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=odp&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert XPS to ODP Files Online using App" %}}

1. Upload XPS files to convert
1. Wait for few seconds or more depending on XPS size
1. Keep an eye on uploading status bar
1. Click the "Convert" button
1. XPS will be converted into ODP document
1. Download the converted ODP file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convert XPS to ODP via Java Automation API" %}}


1. Open XPS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XPS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to ODP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Odp` as SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Few more cases for saving XPS to ODP with other features like Open Encrypted XPS File via Java, Save ODP File with Predefined View Type via Java.

{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Develop XPS File Conversion Application using Java</h2>

Need to develop Java based software application to easily save and export XPS files to ODP document ? With [Aspose.Total for Java](https://products.aspose.com/total/java/), any Java developer can integrate the above API code to program the conversion application across variety of formats including Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, Email files, Images (JPG, PNG, BMP, GIF) and other formats. Powerful Java library for document conversion, supports many popular formats including XPS format. Exporting and rendering documents to other formats, programmers can use Aspose.Total for Java child APIs inlcluding [Aspose.Words for Java](https://products.aspose.com/words/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) and more.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS Conversion Library for Java" %}}

There are alternative options to integrate Aspose.Total for Java onto your system. Please choose one that resembles your needs and follow the step-by-step instructions:<br /><br />

- Use Aspose.Total for Java directly from a Maven based project and include relevant child API in pom.xml.
- Alternatively, one can get a ZIP file from [downloads](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Saving XPS to ODP App Requirements" %}}

Any Operating System that can run the Java Runtime Environment (JRE) can run Aspose.Total for Java. The following lists mostly, but not all, supported Operating Systems. <br /><br />
- Microsoft Windows
- Linux : Ubuntu, OpenSUSE, CentOS and others
- macOS : 10.9 (Mavericks) and later
- Mobile : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}