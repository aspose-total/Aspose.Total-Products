---
title: Esporta PPSM in RTF su Andorid tramite Java
description: Converti PPSM in RTF nelle app mobili senza installare alcun software

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: RTF
otherformats: DOCX DOCM WORDML DOTM OTT ODT DOTX DOC DOT TEXT FLATOPC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi PPSM in RTF su Andorid tramite Java" h2="API di formato file per convertire PPSM in RTF all'interno di app Android senza dipendere da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) consente di manipolare i formati di file all'interno delle applicazioni Android. Utilizzando le API fornite nel pacchetto puoi automatizzare il processo di conversione da PowerPoint PPSM a Word RTF nelle tue app.
Puoi convertire il rtfumento fornito in due passaggi. È possibile utilizzare [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) che è un'API PowerPoint per applicazioni Android per eseguire il rendering di PPSM in HTML. Successivamente, utilizzando l'API di elaborazione dei rtfumenti [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) puoi convertire l'HTML in RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendering da PPSM a RTF in Android" %}}
1. Aprire il file PPSM utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converti PPSM in HTML utilizzando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e imposta Html come SaveFormat
3. Caricare il file HTML convertito utilizzando la classe [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. Salva il rtfumento in formato RTF utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) e imposta Rtf come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words per Andorid tramite Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nel tuo applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-rtfx/" name="PPSM Per RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-rtfm/" name="PPSM Per RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-wordml/" name="PPSM Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-dotm/" name="PPSM Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-ott/" name="PPSM Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-odt/" name="PPSM Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-dotx/" name="PPSM Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-rtf/" name="PPSM Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-dot/" name="PPSM Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-text/" name="PPSM Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-flatopc/" name="PPSM Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-word/" name="PPSM Per WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}