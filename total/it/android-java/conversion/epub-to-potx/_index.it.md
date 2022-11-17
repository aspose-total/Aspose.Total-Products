---
title: Esporta EPUB in POTX in Android
description: API Android per convertire EPUB in POTX senza utilizzare Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: POTX
otherformats: PPTM POWERPOINT SWF PPSX PPT PPS ODP XAML POTM PPSM POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti EPUB in POTX su Android tramite Java" h2="Trasforma EPUB in POTX all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da EPUB a POTX all'interno delle tue applicazioni Android utilizzando due semplici passaggi. Nel primo passaggio puoi esportare EPUB in PPTX utilizzando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Successivamente, utilizzando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), puoi convertire PPTX in POTX. Entrambe le API rientrano nel pacchetto [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare EPUB in POTX" %}}
1. Aprire il file EPUB utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti EPUB in PPTX utilizzando il metodo [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato POTX utilizzando il metodo [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Potx` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Apri il file EPUB protetto da password in Android tramite Java" %}}
Durante il caricamento del formato file EPUB, il documento potrebbe essere protetto da password. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Crea un'immagine in miniatura del file POTX nelle applicazioni Android" %}}
Dopo aver convertito EPUB in POTX, puoi anche creare immagini in miniatura del tuo documento di output. Utilizzando la ricca funzionalità [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) puoi generare immagini in miniatura delle diapositive creando un'istanza della [Presentazione]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Successivamente, puoi ottenere il riferimento di qualsiasi diapositiva desiderata utilizzando il suo ID o indice e ottenere l'immagine in miniatura della diapositiva di riferimento su una scala specificata.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("output.potx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-pptm/" name="EPUB Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-powerpoint/" name="EPUB Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-swf/" name="EPUB Per SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-ppsx/" name="EPUB Per PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-ppt/" name="EPUB Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-pps/" name="EPUB Per PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-potx/" name="EPUB Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-xaml/" name="EPUB Per XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-potm/" name="EPUB Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-ppsm/" name="EPUB Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-pot/" name="EPUB Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/epub-to-otp/" name="EPUB Per OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}