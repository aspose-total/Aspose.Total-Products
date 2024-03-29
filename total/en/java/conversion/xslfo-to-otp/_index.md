---
title: Convert XSLFO to OTP via Java API
description: Java API to Convert XSLFO to OTP without using Microsoft Word
url_ignore: /java/conversion/xslfo-to-otp/
family: total
platformtag: java
feature: conversion
informat: XSLFO
outformat: OTP
otherformats: POTX POTM PPTM SWF ODP XAML POT PPSX PPS POWERPOINT PPT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java API to Export XSLFO to OTP" h2="Export XSLFO to OTP via on premise Java API without using Microsoft<sup>&reg;</sup> PowerPoint or Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for Java is a comprehensive suite of components that enables developers to easily convert XSLFO to OTP within any Java J2SE, J2EE, or J2ME application. The process involves two steps, both of which are made possible by components of the Aspose.Total for Java suite. 

The first step is to export XSLFO to PPTX using Aspose.PDF for Java. This component provides a wide range of features for working with PDF documents, including the ability to convert XSLFO to PPTX. It also offers a range of other features, such as the ability to create, edit, and manipulate PDF documents, as well as the ability to convert PDF documents to other formats. 

The second step is to convert PPTX to OTP using Aspose.Slides for Java. This component provides a comprehensive set of features for working with PowerPoint presentations, including the ability to convert PPTX to OTP. It also offers a range of other features, such as the ability to create, edit, and manipulate PowerPoint presentations, as well as the ability to convert PowerPoint presentations to other formats. 

In summary, Aspose.Total for Java provides a comprehensive suite of components that enables developers to easily convert XSLFO to OTP within any Java J2SE, J2EE, or J2ME application. The process involves two steps, both of which are made possible by components of the Aspose.Total for Java suite. Firstly, XSLFO is exported to PPTX using Aspose.PDF for Java. Secondly, PPTX is converted to OTP using Aspose.Slides for Java. This makes it easy for developers to quickly and easily convert XSLFO to OTP within any Java application.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API to Convert XSLFO to OTP" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class
2. Convert XSLFO to PPTX by using [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) method
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class 
4. Save the document to OTP format using [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) method and set `Otp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) and [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Open Encrypted XSLFO File via Java" %}}
While loading XSLFO file format, your document might be password protected. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) allows you open encrypted documents as well. In order to open the encrypted file, you can initialize new instance of the  [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class and pass filename and password as arguments. 
{{% blocks/products/pf/feature-page-code %}}
```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Save OTP File with Predefined View Type via Java" %}}
After converting XSLFO to OTP, you can also add predefined view type for your presentation. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) provides a facility to set the view type for the generated presentation when it is opened in PowerPoint through the [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) class. The [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) property is used to set the view type by using the [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerator.
{{% blocks/products/pf/feature-page-code %}}
```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}