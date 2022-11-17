---
title: Esporta PPSM in OTT su Andorid tramite Java
description: Converti PPSM in OTT nelle app mobili senza installare alcun software

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: OTT
otherformats: RTF DOC TEXT ODT DOTM WORD DOT FLATOPC DOTX DOCX DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi PPSM in OTT su Andorid tramite Java" h2="API di formato file per convertire PPSM in OTT all'interno di app Android senza dipendere da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) consente di manipolare i formati di file all'interno delle applicazioni Android. Utilizzando le API fornite nel pacchetto puoi automatizzare il processo di conversione da PowerPoint PPSM a Word OTT nelle tue app.
Puoi convertire il ottumento fornito in due passaggi. È possibile utilizzare [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) che è un'API PowerPoint per applicazioni Android per eseguire il rendering di PPSM in HTML. Successivamente, utilizzando l'API di elaborazione dei ottumenti [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) puoi convertire l'HTML in OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendering da PPSM a OTT in Android" %}}
1. Aprire il file PPSM utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converti PPSM in HTML utilizzando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) e imposta Html come SaveFormat
3. Caricare il file HTML convertito utilizzando la classe [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument)
4. Salva il ottumento in formato OTT utilizzando il metodo [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) e imposta Ott come SalvaFormato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.Slides for Android via Java](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) e [Aspose.Words per Andorid tramite Java](https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) nel tuo applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Ottument
Ottument ottument = new Ottument("htmlOutput.html");
// save ottument in OTT format
ottument.save("output.ott",SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-rtf/" name="PPSM Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-ott/" name="PPSM Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-text/" name="PPSM Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-odt/" name="PPSM Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-dotm/" name="PPSM Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-word/" name="PPSM Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-dot/" name="PPSM Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-flatopc/" name="PPSM Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-dotx/" name="PPSM Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-ottx/" name="PPSM Per OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-ottm/" name="PPSM Per OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/ppsm-to-wordml/" name="PPSM Per WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}