---
title: Convert MD to PPTM via Java API
description: Java API to Convert MD to PPTM without using Microsoft Word
url_ignore: /java/conversion/md-to-pptm/
family: total
platformtag: java
feature: conversion
informat: MD
outformat: PPTM
otherformats: POTX PPSX PPT XAML POT SWF PPSM ODP PPS POTM POWERPOINT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export MD to PPTM" h2="Export MD to PPTM via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of APIs that enables developers to easily convert MD to PPTM within any Java J2SE, J2EE, or J2ME application. The process involves two steps. Firstly, Aspose.PDF for Java is used to export MD to PPTX. This API provides a wide range of features for manipulating PDF documents, including the ability to convert PDF to other popular formats. After that, Aspose.Slides for Java is used to convert PPTX to PPTM. This PowerPoint Processing API provides a comprehensive set of features for creating, manipulating, and converting PowerPoint documents. It also supports a wide range of features for working with slides, shapes, text, and other elements. 

Aspose.Total for Java is a powerful and reliable solution for converting MD to PPTM. It is easy to use and provides a comprehensive set of features for manipulating and converting documents. It is also highly scalable and can be used in any Java J2SE, J2EE, or J2ME application. With Aspose.Total for Java, developers can quickly and easily convert MD to PPTM with just a few lines of code.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert MD to PPTM" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert MD to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to PPTM format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Pptm` as SaveFormat
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

{{% blocks/products/pf/feature-page-section  h2="Save PPTM File with Predefined View Type via Java" %}}
After converting MD to PPTM, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section >}}



MD (Markdown) to PPTM (Macro-Enabled PowerPoint) conversion enhances presentation capabilities by combining MD-sourced content with macro-driven automation. PPTM files support dynamic slide manipulation, data binding, and scripted interactions.



{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}



* Automated financial presentations built from MD source data.

* Dynamic dashboards using macros created from Markdown reports.

* Interactive training modules generated from MD documentation.

* Macro-enabled pitch decks sourced from product Markdown files.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}



* CI/CD pipelines generating PPTM decks for reporting teams.

* Auto-updating macro-enabled presentations sourced from repos.

* Batch PPTM creation for corporate training systems.

* Scheduled generation of PPTM-based dashboards using Markdown inputs.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}