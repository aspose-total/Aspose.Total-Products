---
title: Convert XSLFO to SWF via Java API
description: Java API to Convert XSLFO to SWF without using Microsoft Word
url_ignore: /java/conversion/xslfo-to-swf/
family: total
platformtag: java
feature: conversion
informat: XSLFO
outformat: SWF
otherformats: PPS POTX ODP POWERPOINT POT PPT PPSX PPTM OTP PPSM POTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export XSLFO to SWF" h2="Export XSLFO to SWF via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert XSLFO to SWF within any Java J2SE, J2EE, or J2ME application. This suite of components is designed to provide developers with the tools they need to quickly and easily create powerful applications.

The process of converting XSLFO to SWF begins with Aspose.PDF for Java. This component enables developers to export XSLFO to PPTX, which is a PowerPoint presentation format. Once the XSLFO has been converted to PPTX, developers can then use Aspose.Slides for Java to convert the PPTX to SWF. Aspose.Slides for Java is a PowerPoint Processing API that enables developers to quickly and easily convert PPTX to SWF.

Aspose.Total for Java also provides developers with a number of other components that can be used to create powerful applications. These components include Aspose.Words for Java, Aspose.Cells for Java, Aspose.BarCode for Java, Aspose.Email for Java, and Aspose.Imaging for Java. Each of these components provides developers with the tools they need to quickly and easily create powerful applications.

In addition to providing developers with the components they need to quickly and easily convert XSLFO to SWF, Aspose.Total for Java also provides developers with a number of other features. These features include support for a wide range of file formats, support for a wide range of programming languages, and support for a wide range of operating systems.

Overall, Aspose.Total for Java is a comprehensive suite of components that enables developers to quickly and easily convert XSLFO to SWF within any Java J2SE, J2EE, or J2ME application. This suite of components provides developers with the tools they need to quickly and easily create powerful applications. In addition to providing developers with the components they need to quickly and easily convert XSLFO to SWF, Aspose.Total for Java also provides developers with a number of other features, such as support for a wide range of file formats, support for a wide range of programming languages, and support for a wide range of operating systems.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert XSLFO to SWF" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XSLFO to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to SWF format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Swf` as SaveFormat
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
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
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

{{% blocks/products/pf/feature-page-section  h2="Save SWF File with Predefined View Type via Java" %}}
After converting XSLFO to SWF, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}