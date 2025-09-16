---
title: Convert EPUB to PPSM via Java API
description: Java API to Convert EPUB to PPSM without using Microsoft Word
url_ignore: /java/conversion/epub-to-ppsm/
family: total
platformtag: java
feature: conversion
informat: EPUB
outformat: PPSM
otherformats: POTM POT OTP PPS XAML PPSX POWERPOINT PPT ODP POTX PPTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export EPUB to PPSM" h2="Export EPUB to PPSM via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to easily convert EPUB to PPSM within any Java J2SE, J2EE, or J2ME application. This suite of APIs is comprised of Aspose.PDF for Java and Aspose.Slides for Java, both of which are powerful tools for manipulating PDF and PowerPoint documents, respectively. 

To convert EPUB to PPSM, the process begins with Aspose.PDF for Java. This API allows developers to export EPUB documents to PPTX, the PowerPoint XML format. Once the document is in PPTX format, Aspose.Slides for Java can be used to convert the document to PPSM. Aspose.Slides for Java is a PowerPoint Processing API that provides developers with a wide range of features for manipulating PowerPoint documents. It can be used to convert PPTX documents to PPSM, as well as to create, edit, and manipulate presentations. 

Aspose.Total for Java is a great solution for developers who need to convert EPUB to PPSM. It provides an easy-to-use suite of APIs that can be used to quickly and easily convert EPUB documents to PPSM. With Aspose.PDF for Java, developers can export EPUB documents to PPTX, and with Aspose.Slides for Java, they can convert PPTX documents to PPSM. This makes it easy to convert EPUB to PPSM within any Java J2SE, J2EE, or J2ME application.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert EPUB to PPSM" %}}
1. Open EPUB file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert EPUB to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsm` as SaveFormat
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

{{% blocks/products/pf/feature-page-section  h2="Save PPSM File with Predefined View Type via Java" %}}
After converting EPUB to PPSM, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
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

{{< blocks/products/pf/agp/feature-section >}}  
Converting **EPUB to PPSM (Macro-enabled PowerPoint Show)** is essential for generating **interactive slideshow files** from eBooks. PPSM files allow slideshows to include macros for automation, interactivity, and dynamic content updates, making them ideal for educational, corporate, and publishing applications. By transforming EPUB into PPSM, organizations can deliver intelligent presentations that enhance engagement and streamline presentation workflows.  

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}  
- **Automated academic shows** – Generate lecture slides with pre-configured interactive elements.  
- **Training material with macros** – Create instructional presentations with automated navigation or calculations.  
- **Corporate slideshow automation** – Standardize and automate business presentation workflows.  
- **Publishing previews** – Deliver interactive previews of eBook content to clients or stakeholders.  
- **Research presentation playback** – Produce macro-enabled slides for dynamic research presentations.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}  
- **EPUB-to-PPSM pipelines** – Automate conversion of eBooks into macro-enabled slideshow files.  
- **Macro-enabled slideshow creation** – Embed interactivity and automation directly into slides.  
- **Metadata-driven automation** – Populate slideshows using structured eBook data.  
- **Enterprise presentation workflows** – Streamline large-scale production and distribution of interactive slides.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}  

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}