---
title: API Java per convertire RTF in XLSM
description: Converti RTF in XLSM tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url: /it/java/conversion/rtf-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLSM
otherformats: XLAM XLSM ODS FODS TSV DIF XLS XLT XLSB XLTM XLTX XLSX EXCEL SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti RTF in XLSM tramite Java" h2="API Java in loco per convertire RTF in XLSM senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione di RTF in XLSM tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) è un semplice processo in due fasi. Utilizzando l'API di conversione e manipolazione dei rtfumenti ricca di funzionalità [Aspose.Words per Java](https://products.aspose.com/words/java/), puoi esportare RTF in HTML. Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire RTF in XLSM" %}}
1. Aprire il file RTF utilizzando la classe [Rtfument](https://apiference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Converti RTF in HTML utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Caricare il rtfumento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il rtfumento in formato XLSM utilizzando [Salva](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includono [Aspose.Words per Java](https://rtfs.aspose.com/words/java/installation/) e [Aspose.Cells per Java](https://rtfs.aspose.com/cells/java/ installazione/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Prima di convertire RTF in XLSM, è possibile rimuovere le informazioni non utilizzate dal rtfumento RTF tramite [Aspose.Words for Java](https://products.aspose.com/words/java/). A volte potrebbe essere necessario rimuovere le informazioni non utilizzate o duplicate per ridurre le dimensioni del rtfumento di output e il tempo di elaborazione. La classe [CleanupOptions](https://apiference.aspose.com/words/java/com.aspose.words/CleanupOptions) consente di specificare le opzioni per la pulizia dei rtfumenti. Per rimuovere dal rtfumento stili duplicati o semplicemente stili o elenchi inutilizzati, puoi utilizzare il metodo [Cleanup](https://apiference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). È possibile utilizzare [UnusedStyles](https://apiference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://apiference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) per rilevare e rimuovere gli stili contrassegnati come "non utilizzati".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Rimuovere le informazioni inutilizzate da un rtfumento RTF tramite Java" %}}
Dopo aver convertito RTF in XLSM, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) consente di salvare il rtfumento per lo streaming. Se è necessario salvare i file in uno Stream, è necessario creare un oggetto FileOutputStream e quindi [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) il file in quell'oggetto Stream chiamando il metodo di salvataggio di [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xlsm/" name="RTF A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xlt/" name="RTF A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-ods/" name="RTF A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-tsv/" name="RTF A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xls/" name="RTF A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xlsb/" name="RTF A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-fods/" name="RTF A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-dif/" name="RTF A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xltx/" name="RTF A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xlam/" name="RTF A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xlsx/" name="RTF A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-xltm/" name="RTF A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-sxc/" name="RTF A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/rtf-to-excel/" name="RTF A EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}