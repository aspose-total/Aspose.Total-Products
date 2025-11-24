---
title: Convert MD to PPSX via Java API
description: Java API to Convert MD to PPSX without using Microsoft Word
url_ignore: /java/conversion/md-to-ppsx/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: PPSX
otherformats: POTX PPSM POWERPOINT POT SWF PPS POTM PPT XAML ODP OTP PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export MD to PPSX" h2="Export MD to PPSX via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert MD to PPSX within any Java J2SE, J2EE, or J2ME application. The process involves two steps, both of which are made simple by the use of Aspose.Total for Java. 

The first step is to export MD to PPTX. This can be done using Aspose.PDF for Java, a powerful PDF Processing API that allows developers to create, edit, and convert PDF documents. With Aspose.PDF for Java, developers can easily convert MD to PPTX, allowing them to move on to the next step in the process. 

The second step is to convert PPTX to PPSX. This can be done using Aspose.Slides for Java, a powerful PowerPoint Processing API that allows developers to create, edit, and convert PowerPoint documents. With Aspose.Slides for Java, developers can easily convert PPTX to PPSX, allowing them to complete the process of converting MD to PPSX. 

Overall, Aspose.Total for Java makes it easy for developers to convert MD to PPSX within any Java J2SE, J2EE, or J2ME application. By using Aspose.PDF for Java to export MD to PPTX and Aspose.Slides for Java to convert PPTX to PPSX, developers can quickly and easily complete the process.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert MD to PPSX" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPSX format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Ppsx` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted MD File via Java" %}}
While loading MD file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save PPSX File with Predefined View Type via Java" %}}
After converting MD to PPSX, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section >}}



MD (Markdown) to PPSX (PowerPoint Slideshow) conversion produces modern slideshow files that open directly into full-screen mode. PPSX is widely used for auto-running presentations in corporate, retail, and event environments.



{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}



* Auto-playing sales presentations sourced from MD notes.

* Corporate lobby screens created from Markdown content.

* Event slide loops built from MD-based schedules or agendas.

* Continuous product demos derived from Markdown descriptions.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}



* Automated PPSX workflows for signage and display boards.

* Scheduled slideshow generation from Markdown event scripts.

* Batch PPSX creation for use across retail outlets.

* MD-to-PPSX conversions within digital signage platforms.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}