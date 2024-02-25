---
title: Converti il formato JSON in PCL tramite Java
description: Analizza JSON in PCL in Java senza utilizzare Microsoft Word
url_ignore: /it/java/conversion/json-to-pcl/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PCL
otherformats: WORD EPUB ODT RTF DOT FLATOPC PCL DOCM DOC OTT PS DOTX MOBI WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti il formato JSON in PCL tramite Java" h2="API Java on premise per analizzare JSON in PCL senza utilizzare Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/) puoi convertire JSON in PCL nelle tue applicazioni Java in un processo in due fasi. Innanzitutto, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/) puoi analizzare JSON in PDF. Nel secondo passaggio, puoi convertire PDF in PCL utilizzando l'API di elaborazione testi [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in PCL tramite Java" %}}
1. Crea un nuovo oggetto [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) e leggi dati JSON validi dal file
2. Importa il file JSON nel foglio di lavoro utilizzando la classe [JsonUtility](https://apiference.aspose.com/cells/java/com.aspose.cells/JsonUtility) e [Salva](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) come PDF
3. Caricare il documento PDF utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato PCL utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Inoltre, l'API ti consente di impostare le opzioni di layout per il tuo JSON durante l'analisi da JSON a PCL utilizzando [JsonLayoutOptions](https://apiference.aspose.com/cells/java/com.aspose.cells/jsonlayouttions). Ti consente di elaborare Array come una tabella, ignorare i valori null, ignorare il titolo dell'array, ignorare il titolo dell'oggetto, convertire la stringa in numero o data, impostare il formato della data e del numero e impostare lo stile del titolo. Tutte queste opzioni ti consentono di presentare i tuoi dati secondo le tue esigenze. Il frammento di codice seguente mostra come impostare le opzioni di layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Imposta layout e converti formato JSON in PCL tramite Java" %}}
Utilizzando l'API, puoi anche analizzare JSON in PCL con filigrana. Per aggiungere una filigrana al tuo documento PCL, puoi prima convertire il file JSON in PDF e aggiungervi una filigrana. Per aggiungere una filigrana, carica il file PDF appena creato utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document), crea un'istanza di TextWatermarkOptions e imposta le sue proprietà, chiama il metodo Watermark.setText e passa il testo e l'oggetto della filigrana di TextWatermarkOptions. Dopo aver aggiunto la filigrana, è possibile salvare il documento in PCL. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}