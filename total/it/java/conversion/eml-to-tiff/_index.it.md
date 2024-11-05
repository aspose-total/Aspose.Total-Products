---
title: Esporta EML in TIFF tramite Java
description: API Java per convertire EML in TIFF senza utilizzare Microsoft Word o Outlook
url_ignore: /it/java/conversion/eml-to-tiff/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TIFF
otherformats: WORDML DOT OTT DOTM EMF TIFF ODT SVG GIF MD PS DOC XPS PDF EPUB FLATOPC DOCX JPEG DOTX PNG TEXT RTF PCL DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per il rendering di EML su TIFF" h2="Esporta EML in TIFF utilizzando l'API Java locale senza utilizzare dipendenze di terze parti" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione della posta elettronica è una potente funzionalità che gli sviluppatori Java possono integrare all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME tramite [Aspose.Total for Java](https://products.aspose.com/total/java/). Utilizzando due API all'interno del pacchetto puoi convertire Eml EML in TIFF senza dipendenze di terze parti. In primo luogo, puoi utilizzare l'API di manipolazione della posta elettronica [Aspose.Email per Java](https://products.aspose.com/email/java/) per convertire il formato del file EML in HTML. In secondo luogo, puoi eseguire il rendering di HTML in TIFF utilizzando l'API di elaborazione documenti [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire EML in TIFF" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://apiference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando [save](https://apiference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) metodo
3. Carica HTML utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato TIFF utilizzando [save](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e impostare TIFF come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Devi usare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}