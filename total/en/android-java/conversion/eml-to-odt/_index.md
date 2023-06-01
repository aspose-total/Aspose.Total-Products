---
title: Render EML to ODT in Andorid App
description: Export EML to ODT without using Microsoft Word or Outlook in you Andorid applications 
url_ignore: /android-java/conversion/eml-to-odt/
family: total
platformtag: android-java
feature: conversion
informat: EML
outformat: ODT
otherformats: DOT EMF PS WORDML FLATOPC RTF TIFF BMP MD DOCX OTT EPUB SVG DOCM GIF PCL DOTM JPEG DOC PNG DOTX XPS TEXT PDF
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Transform EML to ODT in Andorid Apps" h2="Desing Andorid applications to export EML to ODT by using Andorid via Java API" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-android-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Total" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}
{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for Android Java" >}}
{{% blocks/products/pf/agp/content h2="How to Render EML to ODT in Andorid Applications" %}}
Andorid Apps are easy to use for end users on daily bases. Day by day numbers of Andorid phones users are increasing. Using the powerful [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation libraries you can develope Email manipulation and convertion applications. You can convert EML to ODT by the combination of [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Using the first API you can convert EML file format to HTML and by using second API, you can render HTML as ODT. 
{{% /blocks/products/pf/agp/content %}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert EML to ODT in Andorid" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) class
2. Convert EML to HTML by using [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) method
3. Load HTML by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class 
4. Save the document to ODT format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method and set ODT as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Andorid via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) and [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code for EML to ODT Conversion in Andorid Apps" gistPath="" %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}