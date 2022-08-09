---
title: Render EMAIL a TEXT nell'app Andorid
description: Esporta EMAIL in TEXT senza utilizzare Microsoft Word o Outlook nelle tue applicazioni Andorid
url: /it/android-java/conversion/email-to-text/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: TEXT
otherformats: PNG ODT DOT DOCM BMP RTF XPS MD WORDML FLATOPC EPUB DOTX DOC TIFF PDF DOTM GIF DOCX PS SVG EMF PCL JPEG OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Trasforma EMAIL in TEXT nelle app Andorid" h2="Progettazione di applicazioni Andorid per esportare EMAIL in TEXT utilizzando Andorid tramite API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Le app Andorid sono facili da usare per gli utenti finali su base giornaliera. Giorno dopo giorno il numero di utenti di telefoni Andorid sta aumentando. Utilizzando le potenti librerie [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation puoi sviluppare applicazioni di manipolazione e conversione della posta elettronica. Puoi convertire EMAIL in TEXT combinando [Aspose.Email per Android Java](https://products.aspose.com/email/android-java/) e [Aspose.Words per Andorid Java](https://products.aspose.com/words/android-java/). Usando la prima API puoi convertire il formato di file EMAIL in HTML e usando la seconda API, puoi renderizzare HTML come TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti EMAIL in TEXT in Andorid" %}}
1. Aprire il file EMAIL utilizzando la classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converti EMAIL in HTML utilizzando [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metodo
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato TEXT utilizzando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare TEXT come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.Email per Android tramite Java](https://docs.aspose.com/email/androidjava/installation/) e [Aspose.Words per Andorid tramite Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-png/" name="MSG Per PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-odt/" name="MSG Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-dot/" name="MSG Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-docm/" name="MSG Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-text/" name="MSG Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-rtf/" name="MSG Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-xps/" name="MSG Per XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-md/" name="MSG Per MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-wordml/" name="MSG Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-flatopc/" name="MSG Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-epub/" name="MSG Per EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-dotx/" name="MSG Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-doc/" name="MSG Per DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-tiff/" name="MSG Per TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-pdf/" name="MSG Per PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-dotm/" name="MSG Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-gif/" name="MSG Per GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-docx/" name="MSG Per DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-ps/" name="MSG Per PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-svg/" name="MSG Per SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-emf/" name="MSG Per EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-pcl/" name="MSG Per PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-jpeg/" name="MSG Per JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/msg-to-ott/" name="MSG Per OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}