---
title: Converti DOTM in formato JSON in Android tramite Java
description: Analizza il formato DOTM in JSON in Android tramite Java senza utilizzare Microsoft Word o Excel

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti DOTM in formato JSON in Android tramite Java" h2="Progetta applicazioni Android per esportare DOTM in JSON senza utilizzare Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire DOTM in formato JSON nelle tue applicazioni Android tramite [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Utilizzando l'API di conversione e manipolazione dei dotmumenti [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puoi esportare DOTM in HTML. Successivamente, utilizzando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), puoi convertire HTML in JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti DOTM in formato JSON in Android" %}}
1. Aprire il file DOTM utilizzando la classe [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Converti DOTM in HTML utilizzando [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Carica il dotmumento HTML utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il dotmumento in formato JSON utilizzando [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa le librerie nella tua app.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti il formato DOTM protetto in formato JSON in Android tramite Java" %}}
Utilizzando l'API, puoi anche aprire il dotmumento protetto da password. Se il dotmumento DOTM di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il dotmumento crittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come aprire un dotmumento crittografato con una password.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti DOTM in JSON nell'intervallo in Android tramite Java" %}}
Durante la conversione di DOTM in JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, creare un intervallo di dati da esportare utilizzando il metodo Cells.createRange, chiamare il metodo JsonUtility.exportRangeToJson con i riferimenti di Range & ExportRangeToJsonOptions e scrivere i dati JSON della stringa su file tramite BufferedWriter.write metodo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}