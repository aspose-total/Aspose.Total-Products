---
title: Converti DOCM in formato JSON tramite Java
description: Converti il formato DOCM in JSON tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url_ignore: /it/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti DOCM in formato JSON tramite Java" h2="API Java in loco per convertire DOCM in JSON senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione del formato DOCM in formato JSON tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) è un semplice processo in due fasi. Utilizzando l'API di conversione e manipolazione dei document ricca di funzionalità [Aspose.Words per Java](https://products.aspose.com/words/java/), puoi esportare DOCM in HTML. Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti DOCM in formato JSON tramite Java" %}}
1. Aprire il file DOCM utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
2. Converti DOCM in HTML utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Caricare il document HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il document in formato JSON utilizzando [Save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Utilizzando l'API, puoi anche aprire il document protetto da password. Se il ddocumentDOCM di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il dodocumentrittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come provare ad aprire un docdocumentittografato con una password:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti DOCM protetto in formato JSON tramite Java" %}}
Durante la conversione di DOCM in JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, creare un intervallo di dati da esportare utilizzando il metodo Cells.createRange, chiamare il metodo JsonUtility.exportRangeToJson con i riferimenti di Range & ExportRangeToJsonOptions e scrivere i dati JSON della stringa su file tramite BufferedWriter.write metodo. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ Casi d'Uso Chiave  

- **Pubblicazione dei Dati del Documento su API REST/GraphQL**  
  Servire il contenuto estratto da DOCM come JSON per il consumo diretto delle API in app web e mobili.  

- **Alimentazione di Database NoSQL e Data Lake**  
  Caricare i dati strutturati derivati da DOCM in MongoDB, Elasticsearch o data lake basati su cloud.  

- **Potenziamento dei Dashboard con Feed JSON in Tempo Reale**  
  Trasmettere KPI e metriche basati su documenti nei dashboard BI e negli strumenti di monitoraggio.  

- **Convalida degli Input rispetto allo Schema JSON**  
  Garantire coerenza e integrità allineando i dati dei campi DOCM alle regole dello schema JSON.  

- **Abilitazione di CMS senza Testa o Architetture a Microservizi**  
  Integrare il contenuto DOCM in sistemi distribuiti basati su API dove il JSON è la lingua franca.  

## ⚙️ Scenari di Automazione  

- **Estrazione DOCM-to-JSON con Mappatura dei Campi**  
  Definire mappature per trasformare tabelle, intestazioni e campi in oggetti JSON strutturati.  

- **Funzioni Serverless che Convertano ed Emettano Eventi JSON**  
  Attivare conversioni all'upload del file, emettendo payload JSON a sistemi basati su eventi.  

- **Lavori ETL che Normalizzano Tipi e Chiavi**  
  Standardizzare le esportazioni DOCM in strutture JSON coerenti per analisi successive.  

- **Webhook che Spingono JSON verso Sistemi Successivi**  
  Automatizzare le esportazioni DOCM-to-JSON che alimentano CRM, strumenti ERP o app di terze parti.  

- **Regole di Governance che Rimuovono Macro e PII Prima dell'Esportazione in JSON**  
  Applicare controlli di conformità per garantire output JSON sicuri e sanificati da file abilitati alle macro.  
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}