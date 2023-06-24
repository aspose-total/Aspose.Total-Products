---
title: Convert TEX to POTX via Java API
description: Java API to Convert TEX to POTX without using Microsoft Word
url_ignore: /java/conversion/tex-to-potx/
family: total
platformtag: java
feature: conversion
informat: TEX
outformat: POTX
otherformats: PPSX PPS XAML PPT ODP SWF PPTM POT POWERPOINT OTP PPSM POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export TEX to POTX" h2="Export TEX to POTX via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert TEX to POTX within any Java J2SE, J2EE, or J2ME application. This suite of components is designed to provide developers with the tools they need to quickly and efficiently convert TEX to POTX.

The process of converting TEX to POTX begins with Aspose.PDF for Java. This component enables developers to export TEX to PPTX, which is the first step in the conversion process. Once the TEX file has been exported to PPTX, developers can then use Aspose.Slides for Java to convert the PPTX to POTX. Aspose.Slides for Java is a PowerPoint Processing API that provides developers with the ability to manipulate PowerPoint presentations in a variety of ways.

Once the PPTX has been converted to POTX, developers can then use Aspose.Total for Java to further manipulate the POTX file. This suite of components provides developers with the ability to add, delete, and modify slides, as well as add text, images, and other elements to the presentation. Additionally, Aspose.Total for Java also provides developers with the ability to save the POTX file in a variety of formats, including PDF, HTML, and XPS.

In conclusion, Aspose.Total for Java is an invaluable suite of components that enables developers to quickly and easily convert TEX to POTX within any Java J2SE, J2EE, or J2ME application. This suite of components provides developers with the tools they need to export TEX to PPTX, convert PPTX to POTX, and further manipulate the POTX file. Aspose.Total for Java is the perfect solution for developers who need to quickly and efficiently convert TEX to POTX.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert TEX to POTX" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert TEX to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to POTX format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Potx` as SaveFormat
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
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
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

{{% blocks/products/pf/feature-page-section  h2="Save POTX File with Predefined View Type via Java" %}}
After converting TEX to POTX, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}