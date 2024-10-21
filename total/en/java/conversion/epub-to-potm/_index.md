---
title: Convert EPUB to POTM via Java API
description: Java API to Convert EPUB to POTM without using Microsoft Word
url_ignore: /java/conversion/epub-to-potm/
family: total
platformtag: java
feature: conversion
informat: EPUB
outformat: POTM
otherformats: PPTM OTP PPT PPSM SWF XAML ODP POWERPOINT POT POTX PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export EPUB to POTM" h2="Export EPUB to POTM via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to easily convert EPUB to POTM within any Java J2SE, J2EE, or J2ME application. This suite of APIs provides a powerful and efficient way to convert EPUB to POTM without any hassle.

The process of converting EPUB to POTM involves two steps. Firstly, by using Aspose.PDF for Java, developers can export EPUB to PPTX. This API provides a wide range of features that enable developers to create, edit, and convert PDF documents with ease. It also provides the ability to export EPUB to PPTX with just a few lines of code.

Once the EPUB is converted to PPTX, developers can use Aspose.Slides for Java PowerPoint Processing API to convert PPTX to POTM. This API provides a comprehensive set of features that enable developers to create, edit, and convert PowerPoint documents with ease. It also provides the ability to convert PPTX to POTM with just a few lines of code.

Overall, Aspose.Total for Java is an ideal solution for developers who need to quickly and easily convert EPUB to POTM within any Java J2SE, J2EE, or J2ME application. It provides a powerful and efficient way to convert EPUB to POTM with just a few lines of code. Furthermore, it also provides a wide range of features that enable developers to create, edit, and convert PDF and PowerPoint documents with ease.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert EPUB to POTM" %}}
1. Open EPUB file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert EPUB to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to POTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Potm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted EPUB File via Java" %}}
While loading EPUB file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save POTM File with Predefined View Type via Java" %}}
After converting EPUB to POTM, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
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