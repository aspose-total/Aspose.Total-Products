---
title: Convert CGM to XAML via Java API
description: Java API to Convert CGM to XAML without using Microsoft Word
url_ignore: /java/conversion/cgm-to-xaml/
family: total
platformtag: java
feature: conversion
informat: CGM
outformat: XAML
otherformats: PPSM POWERPOINT PPSX ODP SWF POTM PPS POTX POT OTP PPTM PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export CGM to XAML" h2="Export CGM to XAML via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert CGM to XAML within any Java J2SE, J2EE, or J2ME application. The process involves two steps, both of which are made simple by the use of Aspose.Total for Java. 

The first step is to export the CGM file to PPTX format. This can be done using Aspose.PDF for Java, a powerful PDF Processing API that allows developers to manipulate PDF documents in a variety of ways. With Aspose.PDF for Java, developers can easily convert CGM to PPTX with just a few lines of code. 

The second step is to convert the PPTX file to XAML. This can be done using Aspose.Slides for Java, a powerful PowerPoint Processing API that allows developers to manipulate PowerPoint presentations in a variety of ways. With Aspose.Slides for Java, developers can easily convert PPTX to XAML with just a few lines of code. 

In summary, Aspose.Total for Java makes it easy for developers to convert CGM to XAML within any Java J2SE, J2EE, or J2ME application. By using Aspose.PDF for Java to export the CGM file to PPTX format, and Aspose.Slides for Java to convert the PPTX file to XAML, developers can quickly and easily complete the conversion process.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert CGM to XAML" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert CGM to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to XAML format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Xaml` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-xaml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted CGM File via Java" %}}
While loading CGM file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save XAML File with Predefined View Type via Java" %}}
After converting CGM to XAML, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
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