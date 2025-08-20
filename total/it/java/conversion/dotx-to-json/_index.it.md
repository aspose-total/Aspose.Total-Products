---
title: Converti DOTX in formato JSON tramite Java
description: Converti il formato DOTX in JSON tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url_ignore: /it/java/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti DOTX in formato JSON tramite Java" h2="API Java in loco per convertire DOTX in JSON senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione del formato DOTX in formato JSON tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) è un semplice processo in due fasi. Utilizzando l'API di conversione e manipolazione dei Documenti ricca di funzionalità [Aspose.Words per Java](https://products.aspose.com/words/java/), puoi esportare DOTX in HTML. Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti DOTX in formato JSON tramite Java" %}}
1. Aprire il file DOTX utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
2. Converti DOTX in HTML utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Caricare il Documento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il Documento in formato JSON utilizzando [Save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section h2="DocumentRequisiti di conversione" %}}
Utilizzando l'API, puoi anche aprire il Documento protetto da password. Se il Documento DOTX di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il Documento crittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come provare ad aprire un Documento crittografato con una password:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti DOTX protetto in formato JSON tramite Java" %}}
Durante la conversione di DOTX in JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, creare un intervallo di dati da esportare utilizzando il metodo Cells.createRange, chiamare il metodo JsonUtility.exportRangeToJson con i riferimenti di Range & ExportRangeToJsonOptions e scrivere i dati JSON della stringa su file tramite BufferedWriter.write metodo. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertire **DOTX** in **JSON** consente lo scambio di dati strutturati, l'integrazione API e i flussi di lavoro web moderni, rendendo i dati del documento utilizzabili per i servizi cloud, le app web e i flussi di lavoro di intelligenza artificiale/apprendimento automatico.

## ✅ Principali casi d'uso
- Esportazioni di dati pronti per l'API
- Integrazione con app web
- Servizi cloud
- Flussi di dati
- Preparazione del dataset per l'intelligenza artificiale/apprendimento automatico

## ⚙️ Scenari di automazione
- Flussi di lavoro DOTX-to-JSON
- Generazione automatica di JSON
- Flussi di lavoro API cloud
- Integrazioni di sistemi enterprise
- Automazione del data lake
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}