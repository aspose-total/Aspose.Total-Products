---
title: Esporta EMLX in ODT tramite Java
description: API Java per convertire EMLX in ODT senza utilizzare Microsoft Word o Outlook
url_ignore: /it/java/conversion/emlx-to-odt/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: ODT
otherformats: DOT JPEG PS XPS DOTM DOCM PDF EMF WORDML DOC SVG PNG MD RTF TIFF FLATOPC DOTX OTT ODT GIF EPUB PCL TEXT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per il rendering di EMLX su ODT" h2="Esporta EMLX in ODT utilizzando l'API Java locale senza utilizzare dipendenze di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione della posta elettronica è una potente funzionalità che gli sviluppatori Java possono integrare all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME tramite [Aspose.Total for Java](https://products.aspose.com/total/java/). Utilizzando due API all'interno del pacchetto puoi convertire Emlx EMLX in ODT senza dipendenze di terze parti. In primo luogo, puoi utilizzare l'API di manipolazione della posta elettronica [Aspose.Email per Java](https://products.aspose.com/email/java/) per convertire il formato del file EMLX in HTML. In secondo luogo, puoi eseguire il rendering di HTML in ODT utilizzando l'API di elaborazione documenti [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire EMLX in ODT" %}}
1. Aprire il file EMLX utilizzando la classe [MailMessage](https://apiference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converti EMLX in HTML utilizzando [save](https://apiference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) metodo
3. Carica HTML utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato ODT utilizzando [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare ODT come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Devi usare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}