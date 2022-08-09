---
title: Render EML naar IMAGE in de Andorid-app
description: Exporteer EML naar IMAGE zonder Microsoft Word of Outlook te gebruiken in je Andorid-applicaties
url: /nl/android-java/conversion/eml-to-image/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: MD DOTX OTT FLATOPC DOCM ODT DOTM TIFF PNG DOT DOCX PCL XPS EPUB GIF SVG DOC BMP JPEG WORDML PS PDF RTF EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformeer EML naar IMAGE in Andorid Apps" h2="Andorid-applicaties ontwerpen om EML naar IMAGE te exporteren met behulp van Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps zijn gemakkelijk te gebruiken voor eindgebruikers op dagelijkse basis. Het aantal gebruikers van Andorid-telefoons neemt met de dag toe. Met behulp van de krachtige [Aspose.Total voor Android via Java](https://product.aspose.com/total/android-java/) File Format Automation-bibliotheken kunt u e-mailmanipulatie- en conversietoepassingen ontwikkelen. U kunt EML converteren naar IMAGE door de combinatie van [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Met behulp van de eerste API kunt u het EML-bestandsformaat converteren naar HTML en door de tweede API te gebruiken, kunt u HTML als IMAGE weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer EML naar IMAGE in Andorid" %}}
1. Open het EML-bestand met de klasse [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Converteer EML naar HTML met behulp van [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) )) methode
3. Laad HTML met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in IMAGE-formaat met [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) methode en stel IMAGE in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Eml voor Android via Java](https://docs.aspose.com/eml/androidjava/installation/) en [Aspose.Words voor Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-md/" name="EML Tot MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-dotx/" name="EML Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-ott/" name="EML Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-flatopc/" name="EML Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-docm/" name="EML Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-odt/" name="EML Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-dotm/" name="EML Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-tiff/" name="EML Tot TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-png/" name="EML Tot PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-dot/" name="EML Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-docx/" name="EML Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-pcl/" name="EML Tot PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-xps/" name="EML Tot XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-epub/" name="EML Tot EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-gif/" name="EML Tot GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-svg/" name="EML Tot SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-doc/" name="EML Tot DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-image/" name="EML Tot IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-jpeg/" name="EML Tot JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-wordml/" name="EML Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-ps/" name="EML Tot PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-pdf/" name="EML Tot PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-rtf/" name="EML Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/eml-to-emf/" name="EML Tot EMF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}