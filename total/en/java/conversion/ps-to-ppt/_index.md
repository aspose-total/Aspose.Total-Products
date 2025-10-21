---
title: Convert PS to PPT via Java API
description: Java API to Convert PS to PPT without using Microsoft Word
url_ignore: /java/conversion/ps-to-ppt/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: PPT
otherformats: SWF XAML OTP POTM POWERPOINT POT PPTM PPSM POTX ODP PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export PS to PPT" h2="Export PS to PPT via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PS to PPT within any Java J2SE, J2EE, or J2ME application. This suite of components provides a wide range of features and capabilities that make it easy to convert PS to PPT. 

The first step in the conversion process is to use Aspose.PDF for Java to export PS to PPTX. This component provides a wide range of features and capabilities that make it easy to export PS to PPTX. It supports a wide range of features such as text extraction, image extraction, and page manipulation. It also supports a wide range of formats such as PDF, XPS, and PS. 

Once the PS has been exported to PPTX, the next step is to use Aspose.Slides for Java PowerPoint Processing API to convert PPTX to PPT. This component provides a wide range of features and capabilities that make it easy to convert PPTX to PPT. It supports a wide range of features such as text extraction, image extraction, and page manipulation. It also supports a wide range of formats such as PPT, PPTX, and PPS. 

Aspose.Total for Java makes it easy to convert PS to PPT within any Java J2SE, J2EE, or J2ME application. It provides a wide range of features and capabilities that make it easy to export PS to PPTX and then convert PPTX to PPT. It supports a wide range of features such as text extraction, image extraction, and page manipulation. It also supports a wide range of formats such as PDF, XPS, PS, PPT, PPTX, and PPS.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to PPT" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPT format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppt` as SaveFormat
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

{{% blocks/products/pf/feature-page-section  h2="Save PPT File with Predefined View Type via Java" %}}
After converting PS to PPT, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
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

{{< blocks/products/pf/agp/feature-section >}}

Converting PS (PostScript) files to PPT (legacy PowerPoint format) allows organizations to preserve compatibility with older versions of Microsoft Office. PPT format ensures PostScript slides can be edited and presented across a wide range of environments.

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* Converting PS-based presentations for legacy Office environments.
* Preparing training, corporate, or marketing slides in PPT format.
* Repurposing PostScript diagrams and layouts for backward compatibility.
* Migrating technical visuals to editable legacy PowerPoint presentations.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* Batch PS-to-PPT conversion for corporate archives.
* Integration with workflow tools for automated PPT generation.
* Scheduled conversion of PS reports into legacy presentation formats.
* AI-assisted extraction of diagrams and layouts for editable PPT slides.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}