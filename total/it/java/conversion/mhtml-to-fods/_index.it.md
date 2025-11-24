---
title: API Java per il rendering da MHTML a FODS
description: Esporta MHTML in FODS tramite API Java senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/java/conversion/mhtml-to-fods/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: FODS
otherformats: MD SXC FODS TSV XLT TXT XLSB XLSM EXCEL DIF XLAM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta MHTML in FODS tramite Java" h2="Converti file MHTML in FODS utilizzando l'API Java in locale all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/) puoi integrare la funzione di conversione da MHTML a FODS nelle tue applicazioni Java in un processo in due fasi. In primo luogo, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) è possibile eseguire il rendering da MHTML a XLSX. Nel secondo passaggio, puoi convertire XLSX in FODS utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file MHTML in FODS tramite Java" %}}
1. Aprire il file MHTML utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MHTML in XLSX utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato FODS utilizzando [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells per Java](https://docs.aspose.com/cells/java/installation/) nel tuo pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Se il tuo documento MHTML è protetto da password, non puoi convertirlo in FODS senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti MHTML protetto in FODS tramite Java" %}}
Durante la conversione del file MHTML in FODS, puoi anche aggiungere una filigrana al formato del file FODS di output. Per aggiungere una filigrana, crea una nuova cartella di lavoro per aprire il file XLSX convertito. Seleziona Foglio di lavoro tramite il suo indice, crea una forma e usa la sua funzione addTextEffect, imposta colori, trasparenza e altro. Successivamente puoi salvare il tuo documento XLSX come FODS con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversione da MHTML a FODS (Flat OpenDocument Spreadsheet) crea file di fogli di calcolo aperti basati su XML adatti per LibreOffice o OpenOffice. FODS è ideale per l'archiviazione leggera e portatile dei dati.



{{% blocks/products/pf/agp/feature-section-col title="Casi d'Uso Principali" %}}



* Archiviazione di report tabellari basati sul web per la modifica multipiattaforma.

* Preparazione di modelli di fogli di calcolo open source per team collaborativi.

* Conversione di cruscotti finanziari online in file FODS portatili.

* Condivisione di dati strutturati dal web con utenti non di Excel.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scenari di Automazione" %}}



* Conversione programmata da MHTML a FODS per flussi di lavoro di ufficio open source.

* Elaborazione batch di tabelle online per generare file FODS modificabili.

* Conversione automatica attivata per sistemi di monitoraggio web.

* Integrazione in piattaforme collaborative che richiedono modelli FODS.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}