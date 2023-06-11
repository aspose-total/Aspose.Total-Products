---
title: Convert XSLFO to POWERPOINT via Java API
description: Java API to Convert XSLFO to POWERPOINT without using Microsoft Word
url_ignore: /java/conversion/xslfo-to-powerpoint/
family: total
platformtag: java
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: XAML SWF OTP PPTM ODP POT PPSM POTM PPSX PPS POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export XSLFO to POWERPOINT" h2="Export XSLFO to POWERPOINT via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert XSLFO to POWERPOINT within any Java J2SE, J2EE, J2ME application. This powerful suite of components provides a simple and efficient way to convert XSLFO to POWERPOINT. 

The process of converting XSLFO to POWERPOINT begins with the use of Aspose.PDF for Java. This component enables developers to export XSLFO to PPTX. Once the XSLFO is exported to PPTX, the next step is to use Aspose.Slides for Java PowerPoint Processing API to convert the PPTX to POWERPOINT. This API provides a wide range of features and functions that allow developers to easily manipulate and convert PPTX to POWERPOINT. 

Aspose.Total for Java also provides a number of other features and functions that make it an ideal choice for developers. It provides support for a wide range of file formats, including PDF, XLS, DOC, PPT, and many more. It also provides support for a variety of image formats, including JPEG, PNG, TIFF, and many more. Additionally, it provides support for a variety of document formats, including HTML, XML, and many more. 

Overall, Aspose.Total for Java is an ideal choice for developers who need to quickly and easily convert XSLFO to POWERPOINT within any Java J2SE, J2EE, J2ME application. With its comprehensive suite of components, developers can easily export XSLFO to PPTX and then use Aspose.Slides for Java PowerPoint Processing API to convert the PPTX to POWERPOINT. Additionally, Aspose.Total for Java provides support for a wide range of file formats, image formats, and document formats, making it an ideal choice for developers.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert XSLFO to POWERPOINT" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XSLFO to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPT format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted XSLFO File via Java" %}}
While loading XSLFO file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save POWERPOINT File with Predefined View Type via Java" %}}
After converting XSLFO to POWERPOINT, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
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