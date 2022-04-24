---
title: API Java per convertire DOTX in FODS
description: Converti DOTX in FODS tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url: /it/java/conversion/dotx-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: FODS
otherformats: XLT XLTM XLSM ODS DIF XLAM FODS TSV SXC XLSB XLS EXCEL XLTX XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti DOTX in FODS tramite Java" h2="API Java in loco per convertire DOTX in FODS senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione di DOTX in FODS tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) è un semplice processo in due fasi. Utilizzando l'API di conversione e manipolazione dei dotxumenti ricca di funzionalità [Aspose.Words per Java](https://products.aspose.com/words/java/), puoi esportare DOTX in HTML. Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in FODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire DOTX in FODS" %}}
1. Aprire il file DOTX utilizzando la classe [Dotxument](https://apiference.aspose.com/words/java/com.aspose.words/Dotxument)
2. Converti DOTX in HTML utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Caricare il dotxumento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il dotxumento in formato FODS utilizzando [Salva](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includono [Aspose.Words per Java](https://dotxs.aspose.com/words/java/installation/) e [Aspose.Cells per Java](https://dotxs.aspose.com/cells/java/ installazione/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Prima di convertire DOTX in FODS, è possibile rimuovere le informazioni non utilizzate dal dotxumento DOTX tramite [Aspose.Words for Java](https://products.aspose.com/words/java/). A volte potrebbe essere necessario rimuovere le informazioni non utilizzate o duplicate per ridurre le dimensioni del dotxumento di output e il tempo di elaborazione. La classe [CleanupOptions](https://apiference.aspose.com/words/java/com.aspose.words/CleanupOptions) consente di specificare le opzioni per la pulizia dei dotxumenti. Per rimuovere dal dotxumento stili duplicati o semplicemente stili o elenchi inutilizzati, puoi utilizzare il metodo [Cleanup](https://apiference.aspose.com/words/java/com.aspose.words/Dotxument#cleanup()). È possibile utilizzare [UnusedStyles](https://apiference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://apiference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) per rilevare e rimuovere gli stili contrassegnati come "non utilizzati".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Rimuovere le informazioni inutilizzate da un dotxumento DOTX tramite Java" %}}
Dopo aver convertito DOTX in FODS, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) consente di salvare il dotxumento per lo streaming. Se è necessario salvare i file in uno Stream, è necessario creare un oggetto FileOutputStream e quindi [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) il file in quell'oggetto Stream chiamando il metodo di salvataggio di [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xlsm/" name="DOTX A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xlt/" name="DOTX A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-ods/" name="DOTX A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-tsv/" name="DOTX A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xls/" name="DOTX A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xlsb/" name="DOTX A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-fods/" name="DOTX A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-dif/" name="DOTX A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xltx/" name="DOTX A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xlam/" name="DOTX A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xlsx/" name="DOTX A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-xltm/" name="DOTX A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-sxc/" name="DOTX A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotx-to-excel/" name="DOTX A EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}