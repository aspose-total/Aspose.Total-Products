---
title: Esporta PPS in DOCM su Andorid tramite Java
description: Converti PPS in DOCM nelle app mobili senza installare alcun software
url: /it/android-java/conversion/pps-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCM
otherformats: OTT DOTM FLATOPC DOT RTF DOC TEXT DOCX WORDML WORD DOTX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi PPS in DOCM su Andorid tramite Java" h2="API di formato file per convertire PPS in DOCM all'interno di app Android senza dipendere da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total per Android tramite Java](https://products.aspose.com/total/android-java/) consente di manipolare i formati di file all'interno delle applicazioni Android. Utilizzando le API fornite nel pacchetto puoi automatizzare il processo di conversione da PowerPoint PPS a Word DOCM nelle tue app.
Puoi convertire il docmumento fornito in due passaggi. È possibile utilizzare [Aspose.Slides per Andorid tramite Java](https://products.aspose.com/slides/android-java/) che è un'API PowerPoint per applicazioni Android per eseguire il rendering di PPS in HTML. Successivamente, utilizzando l'API di elaborazione dei docmumenti [Aspose.Words per Android tramite Java](https://products.aspose.com/words/android-java/) puoi convertire l'HTML in DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendering da PPS a DOCM in Android" %}}
1. Aprire il file PPS utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converti PPS in HTML utilizzando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e imposta Html come SaveFormat
3. Caricare il file HTML convertito utilizzando la classe [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument)
4. Salva il docmumento in formato DOCM utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,int)) e imposta Docm come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.Slides per Android tramite Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words per Andorid tramite Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nel tuo applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docmument
Docmument docmument = new Docmument("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-ott/" name="PPS Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-dotm/" name="PPS Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-flatopc/" name="PPS Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-dot/" name="PPS Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-rtf/" name="PPS Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-docm/" name="PPS Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-text/" name="PPS Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-docmx/" name="PPS Per DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-wordml/" name="PPS Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-word/" name="PPS Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-dotx/" name="PPS Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pps-to-odt/" name="PPS Per ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}