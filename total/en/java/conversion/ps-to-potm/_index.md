---
title: Convert PS to POTM via Java API
description: Java API to Convert PS to POTM without using Microsoft Word
url_ignore: /java/conversion/ps-to-potm/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: POTM
otherformats: SWF POTX PPT POWERPOINT PPS PPSM ODP XAML PPTM OTP POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export PS to POTM" h2="Export PS to POTM via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PostScript (PS) to PowerPoint Open XML Macro-Enabled Presentation (POTM) within any Java J2SE, J2EE, or J2ME application. This suite of components provides developers with the tools they need to quickly and efficiently convert PS to POTM.

The process of converting PS to POTM begins with Aspose.PDF for Java, which is a powerful PDF Processing API that enables developers to export PS to PPTX. This API provides developers with a wide range of features, such as the ability to convert PS to PDF, extract text from PDF documents, and convert PDF documents to other popular file formats.

Once the PS has been converted to PPTX, developers can then use Aspose.Slides for Java, a powerful PowerPoint Processing API, to convert the PPTX to POTM. This API provides developers with a wide range of features, such as the ability to create, modify, and convert presentations, as well as the ability to add and manipulate text, shapes, and images.

In addition to the features mentioned above, Aspose.Total for Java also provides developers with a wide range of other components, such as Aspose.Words for Java, which enables developers to create, modify, and convert documents, and Aspose.Cells for Java, which enables developers to create, modify, and convert spreadsheets.

Overall, Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PS to POTM within any Java J2SE, J2EE, or J2ME application. This suite of components provides developers with the tools they need to quickly and efficiently convert PS to POTM, as well as a wide range of other features and components.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to POTM" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to POTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Potm` as SaveFormat
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

{{% blocks/products/pf/feature-page-section  h2="Save POTM File with Predefined View Type via Java" %}}
After converting PS to POTM, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}