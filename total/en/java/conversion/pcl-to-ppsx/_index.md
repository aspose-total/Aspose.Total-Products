---
title: Online PCL to PPSX Conversion or Develop Java based Application to Convert PCL Files
description: Free online app to convert PCL to PPSX files. Java conversion library code for PCL documents. 

family: total
platformtag: Java
feature: conversion
informat: PCL
outformat: PPSX
otherformats: OTP PPTM POTM POTX PPS SWF ODP XAML POWERPOINT POT PPT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Online PCL to PPSX Conversion App and Java Code to Convert PCL Files" h2="Develop powerful Java based PCL conversion and exporting application. Convert single or multiple PCL files to PPSX and other formats via Java automation API. Freely convert PCL files online via app with instant download." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Free Online PCL to PPSX Conversion App" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ppsx&from=pcl" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert PCL to PPSX Files Online using App" %}}

1. Upload PCL files to convert
1. Wait for few seconds or more depending on PCL size
1. Keep an eye on uploading status bar
1. Click the "Convert" button
1. PCL will be converted into PPSX document
1. Download the converted PPSX file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convert PCL to PPSX via Java Automation API" %}}


1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSX format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsx` as SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Java Code for PCL to PPSX Conversion" offSpacer="" %}}
{{< gist "aspose-com-gists" "bfec283bb7a30344c355fa8754a3e3a7" "convert-pcl-to-powerpoint.java" >}}
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Few more cases for saving PCL to PPSX with other features like Open Encrypted PCL File via Java, Save PPSX File with Predefined View Type via Java.

{{% blocks/products/pf/feature-page-code %}}

```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Develop PCL File Conversion Application using Java</h2>

Need to develop Java based software application to easily save and export PCL files to PPSX document ? With [Aspose.Total for Java](https://products.aspose.com/total/java/), any Java developer can integrate the above API code to program the conversion application across variety of formats including Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, Email files, Images (JPG, PNG, BMP, GIF) and other formats. Powerful Java library for document conversion, supports many popular formats including PCL format. Exporting and rendering documents to other formats, programmers can use Aspose.Total for Java child APIs inlcluding [Aspose.Words for Java](https://products.aspose.com/words/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) and more.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PCL Conversion Library for Java" %}}

There are alternative options to integrate Aspose.Total for Java onto your system. Please choose one that resembles your needs and follow the step-by-step instructions:<br /><br />

- Use Aspose.Total for Java directly from a Maven based project and include relevant child API in pom.xml.
- Alternatively, one can get a ZIP file from [downloads](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Saving PCL to PPSX App Requirements" %}}

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