---
title: Converti CGM in OTP tramite API Java
description: API Java per convertire CGM in OTP senza utilizzare Microsoft Word
url: /it/java/conversion/cgm-to-otp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTP
otherformats: XAML PPSX PPT POWERPOINT PPS SWF POTM OTP PPTM POTX POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per esportare CGM in OTP" h2="Esporta CGM in OTP tramite l'API Java locale senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total per Java](https://products.aspose.com/total/java/) puoi facilmente convertire CGM in OTP all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME. Innanzitutto, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puoi esportare CGM in PPTX. Successivamente, utilizzando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, puoi convertire PPTX in OTP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire CGM in OTP" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti CGM in PPTX utilizzando il metodo [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato OTP utilizzando il metodo [save](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Otp` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides per Java](https://docs.aspose.com/slides/java/ installazione/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}Document#Document-java.lang.String-java.lang.String-
Durante il caricamento del formato file CGM, il documento potrebbe essere protetto da password. [Aspose.PDF per Java](https://products.aspose.com/pdf/java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Apri il file CGM crittografato tramite Java" %}}
Dopo aver convertito CGM in OTP, puoi anche aggiungere un tipo di visualizzazione predefinito per la tua presentazione. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornisce una funzione per impostare il tipo di visualizzazione per la presentazione generata quando viene aperta in PowerPoint tramite [ViewProperties](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La proprietà [setLastView](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) viene utilizzata per impostare il tipo di visualizzazione utilizzando [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumeratore. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-pps/" name="CGM A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-swf/" name="CGM A SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-potx/" name="CGM A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-ppsx/" name="CGM A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-potm/" name="CGM A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-ppt/" name="CGM A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-ppsm/" name="CGM A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xaml/" name="CGM A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-otp/" name="CGM A OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-pptm/" name="CGM A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-pot/" name="CGM A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-powerpoint/" name="CGM A POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}