---
title: Esporta PPT in FLATOPC su Andorid tramite Java
description: Converti PPT in FLATOPC nelle app mobili senza installare alcun software
url: /it/android-java/conversion/ppt-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: FLATOPC
otherformats: ODT DOCM TEXT DOTX DOCX WORD WORDML RTF DOT DOTM DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi PPT in FLATOPC su Andorid tramite Java" h2="API di formato file per convertire PPT in FLATOPC all'interno di app Android senza dipendere da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total per Android tramite Java](https://products.aspose.com/total/android-java/) consente di manipolare i formati di file all'interno delle applicazioni Android. Utilizzando le API fornite nel pacchetto puoi automatizzare il processo di conversione da PowerPoint PPT a Word FLATOPC nelle tue app.
Puoi convertire il flatopcumento fornito in due passaggi. È possibile utilizzare [Aspose.Slides per Andorid tramite Java](https://products.aspose.com/slides/android-java/) che è un'API PowerPoint per applicazioni Android per eseguire il rendering di PPT in HTML. Successivamente, utilizzando l'API di elaborazione dei flatopcumenti [Aspose.Words per Android tramite Java](https://products.aspose.com/words/android-java/) puoi convertire l'HTML in FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendering da PPT a FLATOPC in Android" %}}
1. Aprire il file PPT utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converti PPT in HTML utilizzando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e imposta Html come SaveFormat
3. Caricare il file HTML convertito utilizzando la classe [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)
4. Salva il flatopcumento in formato FLATOPC utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int)) e imposta Flatopc come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.Slides per Android tramite Java](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words per Andorid tramite Java](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nel tuo applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-odt/" name="PPT Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-flatopcm/" name="PPT Per FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-text/" name="PPT Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-dotx/" name="PPT Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-flatopcx/" name="PPT Per FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-word/" name="PPT Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-wordml/" name="PPT Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-rtf/" name="PPT Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-dot/" name="PPT Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-dotm/" name="PPT Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-flatopc/" name="PPT Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppt-to-ott/" name="PPT Per OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}