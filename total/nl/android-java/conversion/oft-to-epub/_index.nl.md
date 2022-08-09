---
title: Render OFT naar EPUB in de Andorid-app
description: Exporteer OFT naar EPUB zonder Microsoft Word of Outlook te gebruiken in je Andorid-applicaties
url: /nl/android-java/conversion/oft-to-epub/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: EPUB
otherformats: DOTX DOCX OTT DOC TIFF MD TEXT RTF DOCM JPEG DOTM PNG EMF FLATOPC ODT PS BMP DOT PDF SVG XPS PCL GIF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformeer OFT naar EPUB in Andorid Apps" h2="Andorid-applicaties ontwerpen om OFT naar EPUB te exporteren met behulp van Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps zijn gemakkelijk te gebruiken voor eindgebruikers op dagelijkse basis. Het aantal gebruikers van Andorid-telefoons neemt met de dag toe. Met behulp van de krachtige [Aspose.Total voor Android via Java](https://product.aspose.com/total/android-java/) File Format Automation-bibliotheken kunt u e-mailmanipulatie- en conversietoepassingen ontwikkelen. U kunt OFT converteren naar EPUB door de combinatie van [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Met behulp van de eerste API kunt u het OFT-bestandsformaat converteren naar HTML en door de tweede API te gebruiken, kunt u HTML als EPUB weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer OFT naar EPUB in Andorid" %}}
1. Open het OFT-bestand met de klasse [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Converteer OFT naar HTML met behulp van [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) )) methode
3. Laad HTML met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in EPUB-formaat met [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) methode en stel EPUB in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Oft voor Android via Java](https://docs.aspose.com/oft/androidjava/installation/) en [Aspose.Words voor Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EPUB
document.save("output.epub", SaveFormat.EPUB); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-dotx/" name="OFT Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-docx/" name="OFT Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-ott/" name="OFT Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-doc/" name="OFT Tot DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-tiff/" name="OFT Tot TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-md/" name="OFT Tot MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-text/" name="OFT Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-rtf/" name="OFT Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-docm/" name="OFT Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-jpeg/" name="OFT Tot JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-dotm/" name="OFT Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-png/" name="OFT Tot PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-emf/" name="OFT Tot EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-flatopc/" name="OFT Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-odt/" name="OFT Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-ps/" name="OFT Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-epub/" name="OFT Tot EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-dot/" name="OFT Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-pdf/" name="OFT Tot PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-svg/" name="OFT Tot SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-xps/" name="OFT Tot XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-pcl/" name="OFT Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-gif/" name="OFT Tot GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/oft-to-wordml/" name="OFT Tot WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}