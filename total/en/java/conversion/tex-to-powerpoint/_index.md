---
title: Convert TEX to POWERPOINT via Java API
description: Java API to Convert TEX to POWERPOINT without using Microsoft Word
url_ignore: /java/conversion/tex-to-powerpoint/
family: total
platformtag: java
feature: conversion
informat: TEX
outformat: POWERPOINT
otherformats: PPS PPT POTM PPSX OTP PPSM PPTM SWF POT XAML ODP POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export TEX to POWERPOINT" h2="Export TEX to POWERPOINT via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is an all-in-one suite of components that enables developers to easily convert TEX to POWERPOINT within any Java J2SE, J2EE, or J2ME application. This suite of components is designed to make it easy for developers to quickly and efficiently convert TEX to POWERPOINT. 

The process of converting TEX to POWERPOINT begins with Aspose.PDF for Java. This component enables developers to export TEX to PPTX. Once the TEX document has been converted to PPTX, the next step is to use Aspose.Slides for Java PowerPoint Processing API to convert PPTX to POWERPOINT. This API provides developers with a comprehensive set of features for manipulating PowerPoint presentations, including the ability to convert PPTX to POWERPOINT. 

Once the PPTX document has been converted to POWERPOINT, developers can then use the various features of Aspose.Slides for Java to further manipulate the presentation. This includes the ability to add, delete, and modify slides, as well as the ability to add text, images, and other objects to the presentation. Additionally, developers can also use the API to apply various formatting options to the presentation, such as font size, color, and alignment. 

Overall, Aspose.Total for Java makes it easy for developers to quickly and efficiently convert TEX to POWERPOINT. By using Aspose.PDF for Java to export TEX to PPTX, and then using Aspose.Slides for Java PowerPoint Processing API to convert PPTX to POWERPOINT, developers can quickly and easily create POWERPOINT presentations from TEX documents. Additionally, the API provides developers with a comprehensive set of features for manipulating the presentation, allowing them to customize the presentation to their exact specifications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert TEX to POWERPOINT" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert TEX to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPT format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted TEX File via Java" %}}
While loading TEX file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open TEX document
Document doc = new Document("input.tex", "Your@Password");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save POWERPOINT File with Predefined View Type via Java" %}}
After converting TEX to POWERPOINT, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}