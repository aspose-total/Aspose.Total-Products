---
title: API Java per il rendering da CGM a DIF
description: Esporta CGM in DIF tramite API Java senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/java/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: XLT XLSB XLAM DIF XLTX XLTM SXC TXT EXCEL ODS MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta CGM in DIF tramite Java" h2="Converti file CGM in DIF utilizzando l'API Java in locale all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/) puoi integrare la funzione di conversione da CGM a DIF nelle tue applicazioni Java in un processo in due fasi. In primo luogo, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) è possibile eseguire il rendering da CGM a XLSX. Nel secondo passaggio, puoi convertire XLSX in DIF utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file CGM in DIF tramite Java" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti CGM in XLSX utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato DIF utilizzando [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells per Java](https://docs.aspose.com/cells/java/installation/) nel tuo pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Se il tuo documento CGM è protetto da password, non puoi convertirlo in DIF senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti CGM protetto in DIF tramite Java" %}}
Durante la conversione del file CGM in DIF, puoi anche aggiungere una filigrana al formato del file DIF di output. Per aggiungere una filigrana, crea una nuova cartella di lavoro per aprire il file XLSX convertito. Seleziona Foglio di lavoro tramite il suo indice, crea una forma e usa la sua funzione addTextEffect, imposta colori, trasparenza e altro. Successivamente puoi salvare il tuo documento XLSX come DIF con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Converting i file **Computer Graphics Metafile (CGM)** in **DIF (Data Interchange Format)** è prezioso per le organizzazioni che necessitano di integrare contenuti visivi o strutturati nei sistemi di fogli di calcolo legacy e nei flussi di lavoro di calcolo scientifico. Nei **ambienti aziendali e di ricerca basati su Java**, questa conversione consente una migrazione fluida da formati più datati, supporta la compatibilità con strumenti statistici e facilita la modellazione dei dati strutturati per le applicazioni ingegneristiche. Trasformando i diagrammi CGM in tabelle DIF, i team possono unificare i dati visivi con i set di dati numerici, migliorando l'accessibilità e l'analisi tra le piattaforme.


## ✅ Principali casi d'uso

- **Migrazione dei sistemi di fogli di calcolo legacy**  
  Convertire i dati CGM in DIF per un'importazione senza soluzione di continuità nei vecchi programmi di fogli di calcolo ancora in uso negli ambienti aziendali.

- **Piattaforme di calcolo scientifico**  
  Trasformare i dati CGM grafici in DIF per la compatibilità con gli strumenti di analisi numerica in fisica, chimica e modellazione ambientale.

- **Modellazione dei dati strutturati nelle app di ingegneria**  
  Utilizzare DIF per rappresentare schemi basati su CGM in forma tabellare strutturata per simulazioni ingegneristiche e integrazione di dati CAD.


## ⚙️ Scenari di automazione

- **Librerie Java per la conversione dei fogli di calcolo**  
  Implementare trasformazioni automatizzate da CGM a DIF utilizzando API Java che gestiscono formati compatibili con i fogli di calcolo.

- **Elaborazione batch negli strumenti ETL**  
  Integrare passaggi di conversione nei pipeline Java-powered Extract-Transform-Load per elaborare grandi volumi di dati ingegneristici o di ricerca.

- **Integrazione con i flussi di calcolo statistico**  
  Alimentare automaticamente i file DIF convertiti nei moduli di analisi statistica R, MATLAB o Python attraverso l'orchestrazione dei flussi di lavoro basata su Java.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}