---
title: Converti MHTML in PPSM tramite API Java
description: API Java per convertire MHTML in PPSM senza utilizzare Microsoft Word
url_ignore: /it/java/conversion/mhtml-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: PPSM
otherformats: PPT POWERPOINT POTM OTP PPSM POTX PPSX PPS XAML POT PPTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java per esportare MHTML in PPSM" h2="Esporta MHTML in PPSM tramite l'API Java locale senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total per Java](https://products.aspose.com/total/java/) puoi facilmente convertire MHTML in PPSM all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME. Innanzitutto, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puoi esportare MHTML in PPTX. Successivamente, utilizzando [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, puoi convertire PPTX in PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java per convertire MHTML in PPSM" %}}
1. Aprire il file MHTML utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MHTML in PPTX utilizzando il metodo [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Salvare il documento in formato PPSM utilizzando il metodo [save](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) e impostare ` Ppsm` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Slides per Java](https://docs.aspose.com/slides/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Durante il caricamento del formato file MHTML, il documento potrebbe essere protetto da password. [Aspose.PDF per Java](https://products.aspose.com/pdf/java/) consente di aprire anche documenti crittografati. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Apri il file MHTML crittografato tramite Java" %}}
Dopo aver convertito MHTML in PPSM, puoi anche aggiungere un tipo di visualizzazione predefinito per la tua presentazione. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) fornisce una funzione per impostare il tipo di visualizzazione per la presentazione generata quando viene aperta in PowerPoint tramite [ViewProperties](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties). La proprietà [setLastView](https://apiference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) viene utilizzata per impostare il tipo di visualizzazione utilizzando [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumeratore. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}