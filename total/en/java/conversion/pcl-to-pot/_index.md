---
title: Convert PCL to POT via Java API
description: Java API to Convert PCL to POT without using Microsoft Word
url_ignore: /java/conversion/pcl-to-pot/
family: total
platformtag: java
feature: conversion
informat: PCL
outformat: POT
otherformats: PPS PPSM XAML POTX PPSX OTP POTM PPTM SWF PPT POWERPOINT ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export PCL to POT" h2="Export PCL to POT via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PCL to POT within any Java J2SE, J2EE, or J2ME application. This suite of components provides a powerful set of tools for manipulating and converting PCL documents to POT format. 

The process of converting PCL to POT begins with the use of Aspose.PDF for Java. This component enables developers to export PCL documents to PPTX format. Once the PCL document has been converted to PPTX, Aspose.Slides for Java can be used to convert the PPTX document to POT format. Aspose.Slides for Java is a PowerPoint Processing API that provides developers with a comprehensive set of tools for manipulating and converting PPTX documents to POT format. 

Aspose.Total for Java also provides developers with a range of other components that can be used to manipulate and convert documents. These components include Aspose.Words for Java, Aspose.Cells for Java, Aspose.BarCode for Java, Aspose.Imaging for Java, and Aspose.Email for Java. All of these components can be used to manipulate and convert documents to various formats, including PDF, DOCX, XLSX, and more. 

Overall, Aspose.Total for Java is an ideal solution for developers who need to quickly and easily convert PCL documents to POT format. With the help of Aspose.PDF for Java and Aspose.Slides for Java, developers can easily export PCL documents to PPTX and then convert the PPTX document to POT format. Additionally, Aspose.Total for Java provides developers with a range of other components that can be used to manipulate and convert documents to various formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PCL to POT" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to POT format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pot` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted PCL File via Java" %}}
While loading PCL file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save POT File with Predefined View Type via Java" %}}
After converting PCL to POT, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}