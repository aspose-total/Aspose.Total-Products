---
title: Render MSG to PS in Andorid App
description: Export MSG to PS without using Microsoft Word or Outlook in you Andorid applications 
url_ignore: /android-java/conversion/msg-to-ps/
family: total
platformtag: android-java
feature: conversion
informat: MSG
outformat: PS
otherformats: PCL DOTX WORDML SVG DOCX XPS OTT DOTM TIFF PDF MD PNG DOC RTF GIF DOT BMP FLATOPC TEXT EPUB ODT JPEG EMF DOCM
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Transform MSG to PS in Andorid Apps" h2="Desing Andorid applications to export MSG to PS by using Andorid via Java API" logoImageSrc="/total/images/aspose_total-for-android-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Total" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}
{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for Android Java" >}}
{{% blocks/products/pf/agp/content h2="How to Render MSG to PS in Andorid Applications" %}}
Andorid Apps are easy to use for end users on daily bases. Day by day numbers of Andorid phones users are increasing. Using the powerful [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation libraries you can develope Email manipulation and convertion applications. You can convert MSG to PS by the combination of [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Using the first API you can convert MSG file format to HTML and by using second API, you can render HTML as PS. 
{{% /blocks/products/pf/agp/content %}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/pf/agp/feature-section-col title="Convert MSG to PS in Andorid" %}}
1. Open MSG file using [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) class
2. Convert MSG to HTML by using [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) method
3. Load HTML by using [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) class 
4. Save the document to PS format using [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) method and set PS as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Andorid via Java APIs" %}}
You can easily use Aspose.Total for Android via Java directly from [Maven](https://releases.aspose.com/total/java/) and install [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) and [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in your applications.

Alternatively, you can get a ZIP file from [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code for MSG to PS Conversion in Andorid Apps" gistPath="" %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PS
document.save("output.ps", SaveFormat.PS); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}