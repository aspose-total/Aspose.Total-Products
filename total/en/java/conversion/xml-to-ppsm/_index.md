---
title: Convert XML to PPSM via Java API
description: Java API to Convert XML to PPSM without using Microsoft Word
url_ignore: /java/conversion/xml-to-ppsm/
family: total
platformtag: java
feature: conversion
informat: XML
outformat: PPSM
otherformats: POWERPOINT ODP PPTM OTP PPSX XAML POTX SWF POT POTM PPS PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export XML to PPSM" h2="Export XML to PPSM via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to easily convert XML to PPSM within any Java J2SE, J2EE, or J2ME application. This suite of APIs provides a powerful and efficient way to convert XML to PPSM without any manual intervention. 

The process of converting XML to PPSM begins with Aspose.PDF for Java. This API allows developers to export XML to PPTX, which is a PowerPoint presentation file format. Once the XML has been converted to PPTX, the next step is to use Aspose.Slides for Java to convert the PPTX to PPSM. Aspose.Slides for Java is a PowerPoint Processing API that provides developers with a comprehensive set of features for manipulating PowerPoint presentations. It enables developers to convert PPTX to PPSM with ease. 

The conversion process is simple and straightforward. All that is required is to load the XML file into Aspose.PDF for Java, export it to PPTX, and then use Aspose.Slides for Java to convert the PPTX to PPSM. The entire process can be completed in a matter of minutes, making it an ideal solution for developers who need to quickly and easily convert XML to PPSM. 

Aspose.Total for Java is a comprehensive suite of APIs that makes it easy for developers to convert XML to PPSM within any Java J2SE, J2EE, or J2ME application. It provides a powerful and efficient way to convert XML to PPSM without any manual intervention. By using Aspose.PDF for Java to export XML to PPTX and Aspose.Slides for Java to convert PPTX to PPSM, developers can quickly and easily convert XML to PPSM.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert XML to PPSM" %}}
1. Open XML file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XML to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted XML File via Java" %}}
While loading XML file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save PPSM File with Predefined View Type via Java" %}}
After converting XML to PPSM, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}