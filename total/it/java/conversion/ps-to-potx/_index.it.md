---
title: Converti PS in POTX tramite API Java
description: API Java per convertire PS in POTX senza utilizzare Microsoft Word
url: /it/java/conversion/ps-to-potx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTX
otherformats: PPTM POWERPOINT POT PPSM POTX PPSX PPS PPT POTM OTP XAML SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per esportare PS in POTX" h2="Esporta PS in POTX tramite l'API Java locale senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total per Java](https://products.aspose.com/total/java/) puoi facilmente convertire PS in POTX all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME. Innanzitutto, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puoi esportare PS in PPTX. Successivamente, utilizzando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, puoi convertire PPTX in POTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire PS in POTX" %}}
1. Aprire il file PS utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti PS in PPTX utilizzando il metodo [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato POTX utilizzando il metodo [save](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Potx` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides per Java](https://docs.aspose.com/slides/java/ installazione/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}Document#Document-java.lang.String-java.lang.String-
Durante il caricamento del formato file PS, il documento potrebbe essere protetto da password. [Aspose.PDF per Java](https://products.aspose.com/pdf/java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Apri il file PS crittografato tramite Java" %}}
Dopo aver convertito PS in POTX, puoi anche aggiungere un tipo di visualizzazione predefinito per la tua presentazione. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornisce una funzione per impostare il tipo di visualizzazione per la presentazione generata quando viene aperta in PowerPoint tramite [ViewProperties](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La proprietà [setLastView](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) viene utilizzata per impostare il tipo di visualizzazione utilizzando [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumeratore. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-pps/" name="PS A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-swf/" name="PS A SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-potx/" name="PS A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-ppsx/" name="PS A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-potm/" name="PS A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-ppt/" name="PS A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-ppsm/" name="PS A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-xaml/" name="PS A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-otp/" name="PS A OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-pptm/" name="PS A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-pot/" name="PS A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/ps-to-powerpoint/" name="PS A POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}