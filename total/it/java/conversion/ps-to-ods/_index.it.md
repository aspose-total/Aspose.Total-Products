---
title: API Java per il rendering da PS a ODS
description: Esporta PS in ODS tramite API Java senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/java/conversion/ps-to-ods/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODS
otherformats: ODS EXCEL XLTM XLTX TXT DIF XLSB XLSM XLT MD FODS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta PS in ODS tramite Java" h2="Converti file PS in ODS utilizzando l'API Java in locale all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/) puoi integrare la funzione di conversione da PS a ODS nelle tue applicazioni Java in un processo in due fasi. In primo luogo, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) è possibile eseguire il rendering da PS a XLSX. Nel secondo passaggio, puoi convertire XLSX in ODS utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file PS in ODS tramite Java" %}}
1. Aprire il file PS utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti PS in XLSX utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato ODS utilizzando [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells per Java](https://docs.aspose.com/cells/java/installation/) nel tuo pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Se il tuo documento PS è protetto da password, non puoi convertirlo in ODS senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti PS protetto in ODS tramite Java" %}}
Durante la conversione del file PS in ODS, puoi anche aggiungere una filigrana al formato del file ODS di output. Per aggiungere una filigrana, crea una nuova cartella di lavoro per aprire il file XLSX convertito. Seleziona Foglio di lavoro tramite il suo indice, crea una forma e usa la sua funzione addTextEffect, imposta colori, trasparenza e altro. Successivamente puoi salvare il tuo documento XLSX come ODS con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
"""
{{< blocks/products/pf/agp/feature-section >}}

La conversione dei file PS (PostScript) in ODS (OpenDocument Spreadsheet) consente di importare dati tabulari, grafici e contenuti strutturati dai documenti PS in LibreOffice Calc o in altre piattaforme di fogli di calcolo. Ciò garantisce la portabilità dei dati e la compatibilità tra ambienti open-source.

{{% blocks/products/pf/agp/feature-section-col title="Principali casi d'uso" %}}

* Estrarre tabelle finanziarie o operative da report PS in fogli di calcolo ODS.
* Convertire grafici PS ingegneristici o scientifici per analisi open-source.
* Preparare set di dati per la gestione di progetti collaborativi utilizzando LibreOffice.
* Trasformare layout PS in modelli di fogli di calcolo per report ricorrenti.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* Conversione automatizzata da PS a ODS in pipeline di elaborazione dati.
* Trasformazione batch di report generati da PostScript per analisi su fogli di calcolo.
* Integrazione in soluzioni di fogli di calcolo open-source basate su cloud.
* Estrazione assistita da intelligenza artificiale di grafici e tabelle da PS in formato ODS.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
"""
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}