---
title: Converti WORD in formato JSON in Android tramite Java
description: Analizza il formato WORD in JSON in Android tramite Java senza utilizzare Microsoft Word o Excel

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti WORD in formato JSON in Android tramite Java" h2="Progetta applicazioni Android per esportare WORD in JSON senza utilizzare Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire WORD in formato JSON nelle tue applicazioni Android tramite [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Utilizzando l'API di conversione e manipolazione dei wordumenti [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puoi esportare WORD in HTML. Successivamente, utilizzando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), puoi convertire HTML in JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti WORD in formato JSON in Android" %}}
1. Aprire il file WORD utilizzando la classe [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
2. Converti WORD in HTML utilizzando [Save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Carica il wordumento HTML utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il wordumento in formato JSON utilizzando [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa le librerie nella tua app.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti il formato WORD protetto in formato JSON in Android tramite Java" %}}
Utilizzando l'API, puoi anche aprire il wordumento protetto da password. Se il wordumento WORD di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il wordumento crittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come aprire un wordumento crittografato con una password.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti WORD in JSON nell'intervallo in Android tramite Java" %}}
Durante la conversione di WORD in JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, creare un intervallo di dati da esportare utilizzando il metodo Cells.createRange, chiamare il metodo JsonUtility.exportRangeToJson con i riferimenti di Range & ExportRangeToJsonOptions e scrivere i dati JSON della stringa su file tramite BufferedWriter.write metodo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}