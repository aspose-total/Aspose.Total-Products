---
title: API Java per il rendering da MD a FODS
description: Esporta MD in FODS tramite API Java senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/java/conversion/md-to-fods/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: FODS
otherformats: XLAM TSV SXC XLTX ODS FODS DIF XLSM XLTM XLSB TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta MD in FODS tramite Java" h2="Converti file MD in FODS utilizzando l'API Java in locale all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/) puoi integrare la funzione di conversione da MD a FODS nelle tue applicazioni Java in un processo in due fasi. In primo luogo, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) è possibile eseguire il rendering da MD a XLSX. Nel secondo passaggio, puoi convertire XLSX in FODS utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file MD in FODS tramite Java" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti MD in XLSX utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
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
Se il tuo documento MD è protetto da password, non puoi convertirlo in FODS senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti MD protetto in FODS tramite Java" %}}
Durante la conversione del file MD in FODS, puoi anche aggiungere una filigrana al formato del file FODS di output. Per aggiungere una filigrana, crea una nuova cartella di lavoro per aprire il file XLSX convertito. Seleziona Foglio di lavoro tramite il suo indice, crea una forma e usa la sua funzione addTextEffect, imposta colori, trasparenza e altro. Successivamente puoi salvare il tuo documento XLSX come FODS con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
"""
{{< blocks/products/pf/agp/feature-section >}}



La conversione da MD (Markdown) a FODS (Flat OpenDocument Spreadsheet) produce file di fogli di calcolo basati su XML modificabili, ideali per suite per ufficio open source. FODS mantiene le strutture delle celle, le formule e la formattazione in un layout completamente basato su testo, compatibile con le diverse versioni.



{{% blocks/products/pf/agp/feature-section-col title="Casi d'Uso Principali" %}}



* Esportazione di set di dati Markdown in formati di fogli di calcolo open source.

* Creazione di file strutturati FODS per gli utenti di LibreOffice.

* Importazione di tabelle MD in fogli di calcolo XML piatti per team di sviluppo.

* Mantenimento degli archivi di fogli di calcolo in forma leggibile dal testo.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scenari di Automazione" %}}



* Conversione batch in FODS per una maggiore trasparenza nel controllo delle versioni.

* Integrazione di MD-to-FODS all'interno di pipeline ETL open source.

* Creazione automatizzata di fogli di calcolo per la documentazione governativa o delle ONG.

* Generazione di FODS basata su trigger nei flussi di lavoro di documentazione continua.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
"""
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}