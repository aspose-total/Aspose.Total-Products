---
title: Converti il formato JSON in CHM in Android tramite Java
description: Analizza JSON in CHM in Java senza utilizzare Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: CHM
otherformats: DOC DOT RTF ODT DOTX WORDML MOBI PCL DOCM EPUB FLATOPC WORD OTT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti il formato JSON in CHM nelle applicazioni Android" h2="Analizza da JSON a CHM all'interno di applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire JSON in CHM nelle tue applicazioni Android in un processo in due fasi. In primo luogo, utilizzando la potente API di elaborazione dei fogli di calcolo [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) puoi analizzare JSON in PDF. Nel secondo passaggio, puoi convertire PDF in CHM utilizzando l'API di elaborazione testi [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Entrambe le API rientrano nella famiglia di prodotti [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in CHM in Android tramite Java" %}}
1. Crea un nuovo oggetto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e leggi dati JSON validi dal file
2. Importa il file JSON nel foglio di lavoro utilizzando la classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) e [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) come PDF
3. Carica il documento PDF utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salvare il documento in formato CHM utilizzando [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa le librerie nella tua app.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Imposta layout e converti il formato JSON in CHM in Android tramite Java" %}}
Inoltre, l'API consente di impostare le opzioni di layout per il formato JSON durante l'analisi da JSON a CHM utilizzando [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayouttions). Ti consente di elaborare Array come una tabella, ignorare i valori null, ignorare il titolo dell'array, ignorare il titolo dell'oggetto, convertire la stringa in numero o data, impostare il formato della data e del numero e impostare lo stile del titolo. Tutte queste opzioni ti consentono di presentare i tuoi dati secondo le tue esigenze. Il frammento di codice seguente mostra come impostare le opzioni di layout.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti il formato JSON in CHM con Watermark in Android tramite Java" %}}
Utilizzando l'API, puoi anche convertire JSON in CHM con filigrana. Per aggiungere una filigrana al tuo documento CHM, puoi prima analizzare il file JSON in PDF e aggiungervi una filigrana. Per aggiungere una filigrana, carica il file PDF appena creato utilizzando la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), crea un'istanza di TextWatermarkOptions e imposta le sue proprietà, chiama il metodo Watermark.setText e passa il testo e l'oggetto della filigrana di TextWatermarkOptions. Dopo aver aggiunto la filigrana, è possibile salvare il documento in CHM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}