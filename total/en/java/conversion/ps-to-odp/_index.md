---
title: Convert PS to ODP via Java API
description: Java API to Convert PS to ODP without using Microsoft Word
url_ignore: /java/conversion/ps-to-odp/
family: total
platformtag: java
feature: conversion
informat: PS
outformat: ODP
otherformats: SWF PPS PPTM POTX PPSM PPSX POT OTP XAML PPT POWERPOINT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export PS to ODP" h2="Export PS to ODP via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert PostScript (PS) to OpenDocument Presentation (ODP) within any Java J2SE, J2EE, or J2ME application. This suite of components provides a powerful and efficient way to convert PS to ODP without any manual intervention.

The process of converting PS to ODP involves two steps. Firstly, using Aspose.PDF for Java, developers can export PS to PPTX. This component provides a wide range of features to manipulate PDF documents, including the ability to convert PDF to other popular formats such as PPTX. It also supports a variety of features such as text extraction, image extraction, page manipulation, and more.

Once the PS document is converted to PPTX, developers can use Aspose.Slides for Java to convert PPTX to ODP. This PowerPoint Processing API provides a comprehensive set of features to manipulate PowerPoint presentations, including the ability to convert PPTX to ODP. It also supports a variety of features such as text extraction, image extraction, page manipulation, and more.

Overall, Aspose.Total for Java provides an easy and efficient way to convert PS to ODP within any Java J2SE, J2EE, or J2ME application. It provides a comprehensive set of features to manipulate PDF and PowerPoint documents, allowing developers to quickly and easily convert PS to ODP without any manual intervention.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert PS to ODP" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert PS to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to ODP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Odp` as SaveFormat
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

{{% blocks/products/pf/feature-page-section  h2="Save ODP File with Predefined View Type via Java" %}}
After converting PS to ODP, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section >}}

Converting PS (PostScript) files to ODP (OpenDocument Presentation) enables the transformation of static PostScript slides or diagrams into fully editable presentation formats compatible with LibreOffice Impress and other OpenDocument-compatible tools. This allows seamless reuse of PS content in presentations.

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* Transforming PS-based charts and diagrams into slide presentations.
* Converting PostScript marketing materials into ODP for team presentations.
* Preparing educational or training materials from PS reports for classroom use.
* Migrating technical PS visuals into collaborative, open-source presentation tools.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* Batch PS-to-ODP conversion for recurring presentation workflows.
* Integration into ETL pipelines for automatically generating slide decks.
* Automated conversion for corporate knowledge-sharing portals.
* AI-assisted layout optimization and slide generation from PS files.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}