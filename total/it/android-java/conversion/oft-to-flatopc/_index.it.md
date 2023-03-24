---
title: Render OFT a FLATOPC nell'app Andorid
description: Esporta OFT in FLATOPC senza utilizzare Microsoft Word o Outlook nelle tue applicazioni Andorid

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: FLAT_OPC
otherformats: DOC DOTX ODT DOCM PNG PCL DOCX JPEG PS DOT GIF DOTM TEXT BMP EPUB OTT SVG RTF TIFF MD PDF EMF WORDML XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Trasforma OFT in FLATOPC nelle app Andorid" h2="Progettazione di applicazioni Andorid per esportare OFT in FLATOPC utilizzando Andorid tramite API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Le app Andorid sono facili da usare per gli utenti finali su base giornaliera. Giorno dopo giorno il numero di utenti di telefoni Andorid sta aumentando. Utilizzando le potenti librerie [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation puoi sviluppare applicazioni di manipolazione e conversione della posta elettronica. Puoi convertire OFT in FLATOPC combinando [Aspose.Oft per Android Java](https://products.aspose.com/oft/android-java/) e [Aspose.Words per Andorid Java](https://products.aspose.com/words/android-java/). Usando la prima API puoi convertire il formato di file OFT in HTML e usando la seconda API, puoi renderizzare HTML come FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti OFT in FLATOPC in Andorid" %}}
1. Aprire il file OFT utilizzando la classe [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Converti OFT in HTML utilizzando [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) metodo
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato FLATOPC utilizzando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare FLATOPC come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa [Aspose.Oft per Android tramite Java](https://docs.aspose.com/oft/androidjava/installation/) e [Aspose.Words per Andorid tramite Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.FLAT_OPC
document.save("output.flat_opc", SaveFormat.FLAT_OPC); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}