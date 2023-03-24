---
title: Render OFT naar PDF in de Andorid-app
description: Exporteer OFT naar PDF zonder Microsoft Word of Outlook te gebruiken in je Andorid-applicaties

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PDF
otherformats: GIF XPS DOTX DOC TIFF SVG DOT PCL DOTM OTT FLATOPC RTF TEXT MD ODT WORDML DOCX EMF PS PNG DOCM JPEG BMP EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformeer OFT naar PDF in Andorid Apps" h2="Andorid-applicaties ontwerpen om OFT naar PDF te exporteren met behulp van Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps zijn gemakkelijk te gebruiken voor eindgebruikers op dagelijkse basis. Het aantal gebruikers van Andorid-telefoons neemt met de dag toe. Met behulp van de krachtige [Aspose.Total for Android via Java](https://product.aspose.com/total/android-java/) File Format Automation-bibliotheken kunt u e-mailmanipulatie- en conversietoepassingen ontwikkelen. U kunt OFT converteren naar PDF door de combinatie van [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Met behulp van de eerste API kunt u het OFT-bestandsformaat converteren naar HTML en door de tweede API te gebruiken, kunt u HTML als PDF weergeven. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer OFT naar PDF in Andorid" %}}
1. Open het OFT-bestand met de klasse [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Converteer OFT naar HTML met behulp van [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) )) methode
3. Laad HTML met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in PDF-formaat met [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) methode en stel PDF in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://releases.aspose.com/total/java/) en installeer [Aspose.Oft voor Android via Java](https://docs.aspose.com/oft/androidjava/installation/) en [Aspose.Words voor Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PDF
document.save("output.pdf", SaveFormat.PDF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}