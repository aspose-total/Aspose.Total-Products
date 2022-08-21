---
title: Esporta MD in PPSX in Android
description: API Android per convertire MD in PPSX senza utilizzare Microsoft Word
url: /it/android-java/conversion/md-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: PPSX
otherformats: POWERPOINT OTP PPTM SWF POTX PPT ODP POTM POT PPS PPSM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti MD in PPSX su Android tramite Java" h2="Trasforma MD in PPSX all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da MD a PPSX all'interno delle tue applicazioni Android utilizzando due semplici passaggi. Nel primo passaggio puoi esportare MD in PPTX utilizzando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Successivamente, utilizzando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), puoi convertire PPTX in PPSX. Entrambe le API rientrano nel pacchetto [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare MD in PPSX" %}}
1. Aprire il file MD utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MD in PPTX utilizzando il metodo [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato PPSX utilizzando il metodo [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Ppsx` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Apri il file MD protetto da password in Android tramite Java" %}}
Durante il caricamento del formato file MD, il documento potrebbe essere protetto da password. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea un'immagine in miniatura del file PPSX nelle applicazioni Android" %}}
Dopo aver convertito MD in PPSX, puoi anche creare immagini in miniatura del tuo documento di output. Utilizzando la ricca funzionalità [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) puoi generare immagini in miniatura delle diapositive creando un'istanza della [Presentazione]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Successivamente, puoi ottenere il riferimento di qualsiasi diapositiva desiderata utilizzando il suo ID o indice e ottenere l'immagine in miniatura della diapositiva di riferimento su una scala specificata.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("output.ppsx");
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
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-powerpoint/" name="MD Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-otp/" name="MD Per OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-pptm/" name="MD Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-swf/" name="MD Per SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-potx/" name="MD Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-ppt/" name="MD Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-ppsx/" name="MD Per PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-potm/" name="MD Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-pot/" name="MD Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-pps/" name="MD Per PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-ppsm/" name="MD Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/md-to-xaml/" name="MD Per XAML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}