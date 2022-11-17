---
title: Esporta POT in WORD su Andorid tramite Java
description: Converti POT in WORD nelle app mobili senza installare alcun software

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOCX
otherformats: ODT DOTX TEXT DOC DOT WORDML OTT FLATOPC DOTM DOCX DOCM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi POT in WORD su Andorid tramite Java" h2="API di formato file per convertire POT in WORD all'interno di app Android senza dipendere da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) consente di manipolare i formati di file all'interno delle applicazioni Android. Utilizzando le API fornite nel pacchetto puoi automatizzare il processo di conversione da PowerPoint POT a Word WORD nelle tue app.
Puoi convertire il wordumento fornito in due passaggi. È possibile utilizzare [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) che è un'API PowerPoint per applicazioni Android per eseguire il rendering di POT in HTML. Successivamente, utilizzando l'API di elaborazione dei wordumenti [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) puoi convertire l'HTML in WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendering da POT a WORD in Android" %}}
1. Aprire il file POT utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converti POT in HTML utilizzando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e imposta Html come SaveFormat
3. Caricare il file HTML convertito utilizzando la classe [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
4. Salva il wordumento in formato WORD utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) e imposta Word come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.Slides for Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words per Andorid tramite Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nel tuo applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-odt/" name="POT Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-dotx/" name="POT Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-text/" name="POT Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-word/" name="POT Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-dot/" name="POT Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-wordml/" name="POT Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-ott/" name="POT Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-flatopc/" name="POT Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-dotm/" name="POT Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-wordx/" name="POT Per WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-wordm/" name="POT Per WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pot-to-rtf/" name="POT Per RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}