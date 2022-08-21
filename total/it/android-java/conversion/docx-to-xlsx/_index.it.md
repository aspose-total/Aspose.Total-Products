---
title: API Android per convertire DOCX in XLSX
description: Converti DOCX in XLSX in Android tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url: /it/android-java/conversion/docx-to-xlsx/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLSX
otherformats: XLAM XLSB TSV XLT XLTM DIF XLTX FODS ODS EXCEL CSV XLS XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti DOCX in XLSX nelle applicazioni Android" h2="Esporta DOCX in XLSX in Android tramite Java senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) puoi integrare la funzione di conversione da DOCX a XLSX all'interno delle tue applicazioni Android. In primo luogo, puoi convertire DOCX in HTML utilizzando l'API di conversione e manipolazione dei docxumenti ricca di funzionalità [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), puoi convertire HTML in XLSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per convertire DOCX in XLSX" %}}
1. Aprire il file DOCX utilizzando la classe [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
2. Converti DOCX in HTML utilizzando [Save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Carica il docxumento HTML utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il docxumento in formato XLSX utilizzando [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e install [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) e [Aspose.Words for Android via Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovere le informazioni inutilizzate da un docxumento DOCX in Android tramite Java" %}}
Prima di convertire DOCX in XLSX, puoi rimuovere le informazioni non utilizzate dal docxumento DOCX tramite [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). A volte potrebbe essere necessario rimuovere le informazioni non utilizzate o duplicate per ridurre le dimensioni del docxumento di output e il tempo di elaborazione. La classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) consente di specificare le opzioni per la pulizia dei docxumenti. Per rimuovere dal docxumento stili duplicati o semplicemente stili o elenchi inutilizzati, puoi utilizzare il metodo [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()). È possibile utilizzare [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) per rilevare e rimuovere gli stili contrassegnati come "non utilizzati".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva file XLSX in streaming in Android tramite Java" %}}
Dopo aver convertito DOCX in XLSX, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) consente di salvare il docxumento per lo streaming. Se è necessario salvare i file in uno Stream, è necessario creare un oggetto FileOutputStream e quindi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) il file in quell'oggetto Stream chiamando il metodo di salvataggio di [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xlam/" name="DOCX Per XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xlsb/" name="DOCX Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-tsv/" name="DOCX Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xlt/" name="DOCX Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xltm/" name="DOCX Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-dif/" name="DOCX Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xltx/" name="DOCX Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-fods/" name="DOCX Per FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-ods/" name="DOCX Per ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-excel/" name="DOCX Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xlsx/" name="DOCX Per XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xls/" name="DOCX Per XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-xlsm/" name="DOCX Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/docx-to-sxc/" name="DOCX Per SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}