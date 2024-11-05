---
title: Exporteer MSG naar PDF via Java
description: Java API om MSG naar PDF te converteren zonder Microsoft Word of Outlook te gebruiken
url_ignore: /nl/java/conversion/msg-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: ODT PDF DOCX TEXT TIFF WORDML PCL SVG GIF RTF DOT EMF DOC EPUB FLATOPC JPEG DOTX MD DOCM PNG PS OTT XPS DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API om MSG naar PDF weer te geven" h2="Exporteer MSG naar PDF met behulp van on-premise Java API zonder afhankelijkheden van derden" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-mailconversie is een krachtige functie die Java-ontwikkelaars kunnen integreren in alle Java J2SE-, J2EE-, J2ME-applicaties via [Aspose.Total for Java](https://products.aspose.com/total/java/). Door twee API's binnen het pakket te gebruiken, kunt u e-mail MSG naar PDF converteren zonder afhankelijkheden van derden. Ten eerste kunt u de API voor e-mailmanipulatie [Aspose.Email for Java](https://products.aspose.com/email/java/) gebruiken om de MSG-bestandsindeling naar HTML te converteren. Ten tweede kunt u HTML naar PDF weergeven met behulp van de Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hoe MSG naar PDF te converteren" %}}
1. Open het MSG-bestand met de klasse [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converteer MSG naar HTML met behulp van [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) methode
3. Laad HTML met behulp van de [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) klasse
4. Sla het document op in PDF-formaat met [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) methode en stel PDF in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U moet Aspose.Total voor Java rechtstreeks vanuit een op [Maven](https://releases.aspose.com/total/java/) gebaseerd project gebruiken en neem bibliotheken op in uw po.xml.

U kunt ook een ZIP-bestand krijgen van [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-pdf.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}