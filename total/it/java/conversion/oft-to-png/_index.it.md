---
title: Esporta OFT in PNG tramite Java
description: API Java per convertire OFT in PNG senza utilizzare Microsoft Word o Outlook
url_ignore: /it/java/conversion/oft-to-png/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PNG
otherformats: OTT MD DOCM DOT DOTX RTF JPEG XPS GIF PCL SVG EPUB DOCX FLATOPC TEXT DOTM PS PNG EMF DOC PDF TIFF WORDML ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per il rendering di OFT su PNG" h2="Esporta OFT in PNG utilizzando l'API Java locale senza utilizzare dipendenze di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione della posta elettronica è una potente funzionalità che gli sviluppatori Java possono integrare all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME tramite [Aspose.Total for Java](https://products.aspose.com/total/java/). Utilizzando due API all'interno del pacchetto puoi convertire Oft OFT in PNG senza dipendenze di terze parti. In primo luogo, puoi utilizzare l'API di manipolazione della posta elettronica [Aspose.Oft per Java](https://products.aspose.com/email/java/) per convertire il formato del file OFT in HTML. In secondo luogo, puoi eseguire il rendering di HTML in PNG utilizzando l'API di elaborazione documenti [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire OFT in PNG" %}}
1. Aprire il file OFT utilizzando la classe [MailMessage](https://apiference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converti OFT in HTML utilizzando [save](https://apiference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metodo
3. Carica HTML utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato PNG utilizzando [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare PNG come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Devi usare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
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