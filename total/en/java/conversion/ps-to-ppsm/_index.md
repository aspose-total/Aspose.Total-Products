---
title: Convert PS to PPSM via Java API
description: Java API to Convert PS to PPSM without using Microsoft Word
url_ignore: /java/conversion/ps-to-ppsm/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: PPSM
otherformats: PPS PPSX XAML POWERPOINT POT ODP POTX PPTM OTP POTM SWF PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export PS to PPSM" h2="Export PS to PPSM via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PostScript (PS) to PowerPoint Slide Show (PPSM) within any Java J2SE, J2EE, or J2ME application. This suite of components is designed to provide developers with a comprehensive set of tools to help them create powerful and efficient applications.

The process of converting PS to PPSM involves two steps. Firstly, using Aspose.PDF for Java, developers can export PS to PowerPoint Presentation (PPTX). This component provides a wide range of features that enable developers to create, manipulate, and convert PDF documents. It also provides a powerful set of APIs that allow developers to easily manipulate PDF documents.

Once the PS document has been converted to PPTX, developers can then use Aspose.Slides for Java to convert the PPTX to PPSM. Aspose.Slides for Java is a powerful PowerPoint Processing API that enables developers to create, manipulate, and convert PowerPoint presentations. It provides a wide range of features that enable developers to easily create, manipulate, and convert PowerPoint presentations.

Using Aspose.Total for Java, developers can easily convert PS to PPSM within any Java J2SE, J2EE, or J2ME application. This suite of components provides developers with a comprehensive set of tools to help them create powerful and efficient applications. With Aspose.PDF for Java, developers can export PS to PPTX, and with Aspose.Slides for Java, developers can convert PPTX to PPSM. This makes it easy for developers to quickly and easily convert PS to PPSM.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to PPSM" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted PS File via Java" %}}
While loading PS file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save PPSM File with Predefined View Type via Java" %}}
After converting PS to PPSM, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
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