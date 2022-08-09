---
title: Esporta PDF in OTP in Android
description: API Android per convertire PDF in OTP senza utilizzare Microsoft Word
url: /it/android-java/conversion/pdf-to-otp/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: OTP
otherformats: POTM PPT POT PPSM POTX SWF ODP PPS PPTM POWERPOINT XAML PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti PDF in OTP su Android tramite Java" h2="Trasforma PDF in OTP all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da PDF a OTP all'interno delle tue applicazioni Android utilizzando due semplici passaggi. Nel primo passaggio puoi esportare PDF in PPTX utilizzando [Aspose.PDF per Android tramite Java](https://products.aspose.com/pdf/android-java/). Successivamente, utilizzando [Aspose.Slides per Android tramite Java](https://products.aspose.com/slides/android-java/), puoi convertire PPTX in OTP. Entrambe le API rientrano nel pacchetto [Aspose.Total per Android tramite Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare PDF in OTP" %}}
1. Aprire il file PDF utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti PDF in PPTX utilizzando il metodo [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato OTP utilizzando il metodo [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Otp` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF per Android tramite Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Slides per Android tramite Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Apri il file PDF protetto da password in Android tramite Java" %}}
Durante il caricamento del formato file PDF, il documento potrebbe essere protetto da password. [Aspose.PDF per Android tramite Java](https://products.aspose.com/pdf/android-java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea un'immagine in miniatura del file OTP nelle applicazioni Android" %}}
Dopo aver convertito PDF in OTP, puoi anche creare immagini in miniatura del tuo documento di output. Utilizzando la ricca funzionalità [Aspose.Slides per Android tramite Java](https://products.aspose.com/slides/android-java/) puoi generare immagini in miniatura delle diapositive creando un'istanza della [Presentazione]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation). Successivamente, puoi ottenere il riferimento di qualsiasi diapositiva desiderata utilizzando il suo ID o indice e ottenere l'immagine in miniatura della diapositiva di riferimento su una scala specificata.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("output.otp");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-potm/" name="PDF Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-ppt/" name="PDF Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-pot/" name="PDF Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-ppsm/" name="PDF Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-potx/" name="PDF Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-swf/" name="PDF Per SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-otp/" name="PDF Per OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-pps/" name="PDF Per PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-pptm/" name="PDF Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-powerpoint/" name="PDF Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-xaml/" name="PDF Per XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/pdf-to-ppsx/" name="PDF Per PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}