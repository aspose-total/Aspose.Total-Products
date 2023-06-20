---
title: Export OFT to DOCM via Java 
description: Java API to Convert OFT to DOCM without using Microsoft Word or Outlook 
url_ignore: /java/conversion/oft-to-docm/
family: total
platformtag: java
feature: conversion
informat: OFT
outformat: DOCM
otherformats: PS BMP EPUB DOC TEXT JPEG GIF RTF MD DOTX ODT TIFF OTT PNG PDF WORDML DOCX DOTM SVG DOT EMF FLATOPC PCL XPS
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Java API to Render OFT to DOCM" h2="Export OFT to DOCM by using on premise Java API without using any third party dependencies" logoImageSrc="/total/images/aspose_total-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Total" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}
{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for Java" >}}
{{% blocks/products/pf/agp/content h2="How to Render OFT to DOCM Using Java" %}}
Email conversion is a powerful feature that Java developers can integrate within any Java J2SE, J2EE, J2ME applications via [Aspose.Total for Java](https://products.aspose.com/total/java/). By using two APIs within the package you can convert Email OFT to DOCM without any third party dependencies. Firstly, you can use Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) to convert OFT file format to HTML. Secondly, you can render HTML to DOCM by using Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/). 
{{% /blocks/products/pf/agp/content %}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/pf/agp/feature-section-col title="OFT to DOCM Conversion on Java" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) class
2. Convert OFT to HTML by using [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) method
3. Load HTML by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class 
4. Save the document to DOCM format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method and set DOCM as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Java File Format APIs" %}}
You can easily use Aspose.Total for Java directly from a [Maven](https://releases.aspose.com/total/java/) based project and include [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) and [Aspose.Email for Java](https://docs.aspose.com/email/java/installation/) in your pom.xml.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code for OFT to DOCM Rendering" gistPath="" %}}
```cs// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCM
document.save("output.docm", SaveFormat.DOCM);   
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}