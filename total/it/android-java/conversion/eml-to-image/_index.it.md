---
title: Render EML a IMAGE nell'app Andorid
description: Esporta EML in IMAGE senza utilizzare Microsoft Word o Outlook nelle tue applicazioni Andorid

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: MD DOTX OTT FLATOPC DOCM ODT DOTM TIFF PNG DOT DOCX PCL XPS EPUB GIF SVG DOC BMP JPEG WORDML PS PDF RTF EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Trasforma EML in IMAGE nelle app Andorid" h2="Progettazione di applicazioni Andorid per esportare EML in IMAGE utilizzando Andorid tramite API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Le app Andorid sono facili da usare per gli utenti finali su base giornaliera. Giorno dopo giorno il numero di utenti di telefoni Andorid sta aumentando. Utilizzando le potenti librerie [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) File Format Automation puoi sviluppare applicazioni di manipolazione e conversione della posta elettronica. Puoi convertire EML in IMAGE combinando [Aspose.Eml per Android Java](https://products.aspose.com/eml/android-java/) e [Aspose.Words per Andorid Java](https://products.aspose.com/words/android-java/). Usando la prima API puoi convertire il formato di file EML in HTML e usando la seconda API, puoi renderizzare HTML come IMAGE. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti EML in IMAGE in Andorid" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) metodo
3. Carica HTML utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato IMAGE utilizzando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare IMAGE come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa [Aspose.Eml per Android tramite Java](https://docs.aspose.com/eml/androidjava/installation/) e [Aspose.Words per Andorid tramite Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}