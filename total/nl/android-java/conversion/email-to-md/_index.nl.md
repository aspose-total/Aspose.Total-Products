---
title: Render EMAIL naar MD in de Andorid-app
description: Exporteer EMAIL naar MD zonder Microsoft Word of Outlook te gebruiken in je Andorid-applicaties
url: /nl/android-java/conversion/email-to-md/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: MD
otherformats: OTT PCL PDF WORDML XPS EPUB DOCM EMF DOT SVG RTF DOC GIF DOTX DOTM TIFF PS JPEG BMP TEXT DOCX PNG FLATOPC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformeer EMAIL naar MD in Andorid Apps" h2="Andorid-applicaties ontwerpen om EMAIL naar MD te exporteren met behulp van Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps zijn gemakkelijk te gebruiken voor eindgebruikers op dagelijkse basis. Het aantal gebruikers van Andorid-telefoons neemt met de dag toe. Met behulp van de krachtige [Aspose.Total voor Android via Java](https://product.aspose.com/total/android-java/) File Format Automation-bibliotheken kunt u e-mailmanipulatie- en conversietoepassingen ontwikkelen. U kunt EMAIL converteren naar MD door de combinatie van [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Met behulp van de eerste API kunt u het EMAIL-bestandsformaat converteren naar HTML en door de tweede API te gebruiken, kunt u HTML als MD weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer EMAIL naar MD in Andorid" %}}
1. Open het EMAIL-bestand met de klasse [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converteer EMAIL naar HTML met behulp van [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) )) methode
3. Laad HTML met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in MD-formaat met [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) methode en stel MD in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Email voor Android via Java](https://docs.aspose.com/email/androidjava/installation/) en [Aspose.Words voor Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.MD
document.save("output.md", SaveFormat.MD); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-ott/" name="MSG Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-pcl/" name="MSG Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-pdf/" name="MSG Tot PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-wordml/" name="MSG Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-xps/" name="MSG Tot XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-epub/" name="MSG Tot EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-docm/" name="MSG Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-emf/" name="MSG Tot EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-dot/" name="MSG Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-svg/" name="MSG Tot SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-rtf/" name="MSG Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-doc/" name="MSG Tot DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-gif/" name="MSG Tot GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-dotx/" name="MSG Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-dotm/" name="MSG Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-tiff/" name="MSG Tot TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-ps/" name="MSG Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-jpeg/" name="MSG Tot JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-md/" name="MSG Tot MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-text/" name="MSG Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-docx/" name="MSG Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-png/" name="MSG Tot PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-flatopc/" name="MSG Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/msg-to-odt/" name="MSG Tot ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}