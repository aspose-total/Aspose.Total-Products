---
title: Esporta XSLFO in PPSM in Android
description: API Android per convertire XSLFO in PPSM senza utilizzare Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPSM
otherformats: PPT POTX POT PPS POWERPOINT PPTM POTM XAML ODP OTP PPSX SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti XSLFO in PPSM su Android tramite Java" h2="Trasforma XSLFO in PPSM all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da XSLFO a PPSM all'interno delle tue applicazioni Android utilizzando due semplici passaggi. Nel primo passaggio puoi esportare XSLFO in PPTX utilizzando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Successivamente, utilizzando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), puoi convertire PPTX in PPSM. Entrambe le API rientrano nel pacchetto [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare XSLFO in PPSM" %}}
1. Aprire il file XSLFO utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti XSLFO in PPTX utilizzando il metodo [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato PPSM utilizzando il metodo [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Ppsm` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Apri il file XSLFO protetto da password in Android tramite Java" %}}
Durante il caricamento del formato file XSLFO, il documento potrebbe essere protetto da password. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Crea un'immagine in miniatura del file PPSM nelle applicazioni Android" %}}
Dopo aver convertito XSLFO in PPSM, puoi anche creare immagini in miniatura del tuo documento di output. Utilizzando la ricca funzionalità [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) puoi generare immagini in miniatura delle diapositive creando un'istanza della [Presentazionereference.aspose.com/slides/java/com.aspose.slides/Presentation). Successivamente, puoi ottenere il riferimento di qualsiasi diapositiva desiderata utilizzando il suo ID o indice e ottenere l'immagine in miniatura della diapositiva di riferimento su una scala specificata.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("output.ppsm");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}