---
title: Convert MD to PPS via Java API
description: Java API to Convert MD to PPS without using Microsoft Word
url_ignore: /java/conversion/md-to-pps/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: PPS
otherformats: PPSM OTP POT POWERPOINT XAML ODP SWF POTX POTM PPSX PPT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export MD to PPS" h2="Export MD to PPS via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to easily convert MD to PPS within any Java J2SE, J2EE, or J2ME application. This suite of APIs provides a wide range of features and capabilities that make it easy to convert MD to PPS quickly and efficiently. 

The first step in the process is to use Aspose.PDF for Java to export MD to PPTX. This API provides a wide range of features and capabilities that make it easy to convert MD to PPTX quickly and efficiently. It supports a variety of formats, including PDF, XPS, and HTML, and provides a range of features such as text extraction, image extraction, and page manipulation. 

Once the MD has been exported to PPTX, the next step is to use Aspose.Slides for Java PowerPoint Processing API to convert PPTX to PPS. This API provides a wide range of features and capabilities that make it easy to convert PPTX to PPS quickly and efficiently. It supports a variety of formats, including PPTX, PPT, and PPS, and provides a range of features such as text extraction, image extraction, and page manipulation. 

In conclusion, Aspose.Total for Java is a comprehensive suite of APIs that makes it easy to convert MD to PPS within any Java J2SE, J2EE, or J2ME application. By using Aspose.PDF for Java to export MD to PPTX and Aspose.Slides for Java PowerPoint Processing API to convert PPTX to PPS, developers can quickly and efficiently convert MD to PPS.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert MD to PPS" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPS format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pps` as SaveFormat
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

{{% blocks/products/pf/feature-page-section  h2="Save PPS File with Predefined View Type via Java" %}}
After converting MD to PPS, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section >}}



MD (Markdown) to PPS (PowerPoint Slideshow) conversion is ideal for turning lightweight content into auto-run presentation files. PPS opens directly as a slideshow, making it perfect for kiosks, displays, and looping presentations.



{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}



* Creating looping kiosk presentations from Markdown notes.

* Auto-run product displays generated from MD descriptions.

* Slideshow-based event displays sourced from MD schedules.

* Museum, retail, or expo displays created directly from Markdown.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}



* Batch generation of PPS slideshows for digital signage.

* Automated MD-to-PPS pipelines for event management teams.

* Scheduled slideshow creation from Markdown announcements.

* Dashboard-driven generation of looping presentation files.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}