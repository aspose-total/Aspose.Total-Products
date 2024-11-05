---
title: Esporta MSG in TEXT tramite Java
description: API Java per convertire MSG in TEXT senza utilizzare Microsoft Word o Outlook
url_ignore: /it/java/conversion/msg-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: FLATOPC EMF WORDML TIFF PDF TEXT ODT PS SVG MD PNG DOTX GIF DOC RTF PCL DOTM DOCM OTT JPEG EPUB DOT XPS DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per il rendering di MSG su TEXT" h2="Esporta MSG in TEXT utilizzando l'API Java locale senza utilizzare dipendenze di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione della posta elettronica è una potente funzionalità che gli sviluppatori Java possono integrare all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME tramite [Aspose.Total for Java](https://products.aspose.com/total/java/). Utilizzando due API all'interno del pacchetto puoi convertire Msg MSG in TEXT senza dipendenze di terze parti. In primo luogo, puoi utilizzare l'API di manipolazione della posta elettronica [Aspose.Email per Java](https://products.aspose.com/email/java/) per convertire il formato del file MSG in HTML. In secondo luogo, puoi eseguire il rendering di HTML in TEXT utilizzando l'API di elaborazione documenti [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire MSG in TEXT" %}}
1. Aprire il file MSG utilizzando la classe [MailMessage](https://apiference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. Converti MSG in HTML utilizzando [save](https://apiference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) metodo
3. Carica HTML utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato TEXT utilizzando [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare TEXT come SaveFormat
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