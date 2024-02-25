---
title: Exporteer OFT naar JPEG via Java
description: Java API om OFT naar JPEG te converteren zonder Microsoft Word of Outlook te gebruiken
url_ignore: /nl/java/conversion/oft-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: JPEG
otherformats: SVG DOCX WORDML DOC DOTX DOTM TEXT PCL XPS OTT PDF GIF FLATOPC MD EPUB TIFF PNG PS DOCM RTF DOT EMF JPEG ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om OFT naar JPEG weer te geven" h2="Exporteer OFT naar JPEG met behulp van on-premise Java API zonder afhankelijkheden van derden" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-mailconversie is een krachtige functie die Java-ontwikkelaars kunnen integreren in alle Java J2SE-, J2EE-, J2ME-applicaties via [Aspose.Total for Java](https://products.aspose.com/total/java/). Door twee API's binnen het pakket te gebruiken, kunt u e-mail OFT naar JPEG converteren zonder afhankelijkheden van derden. Ten eerste kunt u de API voor e-mailmanipulatie [Aspose.Oft for Java](https://products.aspose.com/email/java/) gebruiken om de OFT-bestandsindeling naar HTML te converteren. Ten tweede kunt u HTML naar JPEG weergeven met behulp van de Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hoe OFT naar JPEG te converteren" %}}
1. Open het OFT-bestand met de klasse [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converteer OFT naar HTML met behulp van [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) methode
3. Laad HTML met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in JPEG-formaat met [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) methode en stel JPEG in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U moet Aspose.Total voor Java rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.JPEG
document.save("output.jpeg", SaveFormat.JPEG);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}