---
title: Converti PDF in POWERPOINT tramite API Java
description: API Java per convertire PDF in POWERPOINT senza utilizzare Microsoft Word
url: /it/java/conversion/pdf-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PPT
otherformats: POWERPOINT POTM POT OTP PPTM PPSM PPS SWF PPSX POTX XAML PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per esportare PDF in POWERPOINT" h2="Esporta PDF in POWERPOINT tramite l'API Java locale senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total per Java](https://products.aspose.com/total/java/) puoi facilmente convertire PDF in POWERPOINT all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME. Innanzitutto, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puoi esportare PDF in PPTX. Successivamente, utilizzando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, puoi convertire PPTX in POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire PDF in POWERPOINT" %}}
1. Aprire il file PDF utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti PDF in PPTX utilizzando il metodo [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato POWERPOINT utilizzando il metodo [save](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Powerpoint` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides per Java](https://docs.aspose.com/slides/java/ installazione/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante il caricamento del formato file PDF, il documento potrebbe essere protetto da password. [Aspose.PDF per Java](https://products.aspose.com/pdf/java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Apri il file PDF crittografato tramite Java" %}}
Dopo aver convertito PDF in POWERPOINT, puoi anche aggiungere un tipo di visualizzazione predefinito per la tua presentazione. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornisce una funzione per impostare il tipo di visualizzazione per la presentazione generata quando viene aperta in PowerPoint tramite [ViewProperties](https:/ /apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La proprietà [setLastView](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) viene utilizzata per impostare il tipo di visualizzazione utilizzando [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumeratore. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-pps/" name="PDF A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-swf/" name="PDF A SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-potx/" name="PDF A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-ppsx/" name="PDF A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-potm/" name="PDF A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-ppt/" name="PDF A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-ppsm/" name="PDF A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xaml/" name="PDF A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-otp/" name="PDF A OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-pptm/" name="PDF A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-pot/" name="PDF A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-powerpoint/" name="PDF A POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}