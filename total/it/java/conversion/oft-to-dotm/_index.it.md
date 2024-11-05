---
title: Esporta OFT in DOTM tramite Java
description: API Java per convertire OFT in DOTM senza utilizzare Microsoft Word o Outlook
url_ignore: /it/java/conversion/oft-to-dotm/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOTM
otherformats: MD DOCM PS GIF XPS DOC DOT ODT DOTM EMF OTT DOTX SVG TEXT WORDML DOCX RTF PNG TIFF FLATOPC PDF EPUB JPEG PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per il rendering di OFT su DOTM" h2="Esporta OFT in DOTM utilizzando l'API Java locale senza utilizzare dipendenze di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione della posta elettronica è una potente funzionalità che gli sviluppatori Java possono integrare all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME tramite [Aspose.Total for Java](https://products.aspose.com/total/java/). Utilizzando due API all'interno del pacchetto puoi convertire Oft OFT in DOTM senza dipendenze di terze parti. In primo luogo, puoi utilizzare l'API di manipolazione della posta elettronica [Aspose.Oft per Java](https://products.aspose.com/email/java/) per convertire il formato del file OFT in HTML. In secondo luogo, puoi eseguire il rendering di HTML in DOTM utilizzando l'API di elaborazione documenti [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire OFT in DOTM" %}}
1. Aprire il file OFT utilizzando la classe [MailMessage](https://apiference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converti OFT in HTML utilizzando [save](https://apiference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metodo
3. Carica HTML utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato DOTM utilizzando [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare DOTM come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Devi usare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}