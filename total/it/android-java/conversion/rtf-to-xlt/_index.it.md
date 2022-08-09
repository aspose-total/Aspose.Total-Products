---
title: API Android per convertire RTF in XLT
description: Converti RTF in XLT in Android tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url: /it/android-java/conversion/rtf-to-xlt/
family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLT
otherformats: XLSB TSV XLS ODS XLTX DIF CSV XLSM FODS EXCEL XLAM XLSX XLTM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti RTF in XLT nelle applicazioni Android" h2="Esporta RTF in XLT in Android tramite Java senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total per Android tramite Java](https://products.aspose.com/total/android-java/) puoi integrare la funzione di conversione da RTF a XLT all'interno delle tue applicazioni Android. In primo luogo, puoi convertire RTF in HTML utilizzando l'API di conversione e manipolazione dei rtfumenti ricca di funzionalità [Aspose.Words per Android tramite Java](https://products.aspose.com/words/android-java/). Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), puoi convertire HTML in XLT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per convertire RTF in XLT" %}}
1. Aprire il file RTF utilizzando la classe [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Converti RTF in HTML utilizzando [Salva](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Carica il rtfumento HTML utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il rtfumento in formato XLT utilizzando [Salva](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e install [Aspose.Cells per Android tramite Java](https://rtfs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) e [Aspose.Words per Android tramite Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovere le informazioni inutilizzate da un rtfumento RTF in Android tramite Java" %}}
Prima di convertire RTF in XLT, puoi rimuovere le informazioni non utilizzate dal rtfumento RTF tramite [Aspose.Words per Android tramite Java](https://products.aspose.com/words/android-java/). A volte potrebbe essere necessario rimuovere le informazioni non utilizzate o duplicate per ridurre le dimensioni del rtfumento di output e il tempo di elaborazione. La classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) consente di specificare le opzioni per la pulizia dei rtfumenti. Per rimuovere dal rtfumento stili duplicati o semplicemente stili o elenchi inutilizzati, puoi utilizzare il metodo [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). È possibile utilizzare [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) per rilevare e rimuovere gli stili contrassegnati come "non utilizzati".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva file XLT in streaming in Android tramite Java" %}}
Dopo aver convertito RTF in XLT, [Aspose.Cells per Android tramite Java](https://products.aspose.com/cells/android-java/) consente di salvare il rtfumento per lo streaming. Se è necessario salvare i file in uno Stream, è necessario creare un oggetto FileOutputStream e quindi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) il file in quell'oggetto Stream chiamando il metodo di salvataggio di [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xlsb/" name="RTF Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-tsv/" name="RTF Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xls/" name="RTF Per XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-ods/" name="RTF Per ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xltx/" name="RTF Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-dif/" name="RTF Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xlt/" name="RTF Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xlsm/" name="RTF Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-fods/" name="RTF Per FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-excel/" name="RTF Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xlam/" name="RTF Per XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xlsx/" name="RTF Per XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-xltm/" name="RTF Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/rtf-to-sxc/" name="RTF Per SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}