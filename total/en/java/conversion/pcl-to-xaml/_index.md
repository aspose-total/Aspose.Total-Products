---
title: Convert PCL to XAML via Java API
description: Java API to Convert PCL to XAML without using Microsoft Word
url_ignore: /java/conversion/pcl-to-xaml/
family: total
platformtag: java
feature: conversion
informat: PCL
outformat: XAML
otherformats: PPSM PPTM POTM PPSX PPT POT PPS POWERPOINT SWF OTP ODP POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export PCL to XAML" h2="Export PCL to XAML via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PCL to XAML within any Java J2SE, J2EE, or J2ME application. This suite of components is designed to provide a comprehensive set of tools for developers to quickly and easily convert PCL to XAML.

The first step in the process is to use Aspose.PDF for Java to export PCL to PPTX. This component provides a powerful set of features that enable developers to quickly and easily convert PCL to PPTX. It also provides a range of features that enable developers to customize the output, such as setting the page size, orientation, and margins.

Once the PCL has been converted to PPTX, the next step is to use Aspose.Slides for Java PowerPoint Processing API to convert PPTX to XAML. This component provides a comprehensive set of features that enable developers to quickly and easily convert PPTX to XAML. It also provides a range of features that enable developers to customize the output, such as setting the page size, orientation, and margins.

In conclusion, Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PCL to XAML within any Java J2SE, J2EE, or J2ME application. It provides a powerful set of features that enable developers to quickly and easily convert PCL to PPTX, and then convert PPTX to XAML. It also provides a range of features that enable developers to customize the output, such as setting the page size, orientation, and margins.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PCL to XAML" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PCL to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to XAML format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Xaml` as SaveFormat
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
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);   
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

{{% blocks/products/pf/feature-page-section  h2="Save XAML File with Predefined View Type via Java" %}}
After converting PCL to XAML, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}