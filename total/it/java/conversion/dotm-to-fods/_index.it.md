---
title: API Java per convertire DOTM in FODS
description: Converti DOTM in FODS tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url: /it/java/conversion/dotm-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: FODS
otherformats: XLT TSV DIF XLSM FODS EXCEL XLSX XLS XLTX ODS SXC XLSB XLTM XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti DOTM in FODS tramite Java" h2="API Java in loco per convertire DOTM in FODS senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione di DOTM in FODS tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) è un semplice processo in due fasi. Utilizzando l'API di conversione e manipolazione dei dotmumenti ricca di funzionalità [Aspose.Words per Java](https://products.aspose.com/words/java/), puoi esportare DOTM in HTML. Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in FODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire DOTM in FODS" %}}
1. Aprire il file DOTM utilizzando la classe [Dotmument](https://apiference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Converti DOTM in HTML utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Caricare il dotmumento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il dotmumento in formato FODS utilizzando [Salva](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includono [Aspose.Words per Java](https://dotms.aspose.com/words/java/installation/) e [Aspose.Cells per Java](https://dotms.aspose.com/cells/java/ installazione/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Prima di convertire DOTM in FODS, è possibile rimuovere le informazioni non utilizzate dal dotmumento DOTM tramite [Aspose.Words for Java](https://products.aspose.com/words/java/). A volte potrebbe essere necessario rimuovere le informazioni non utilizzate o duplicate per ridurre le dimensioni del dotmumento di output e il tempo di elaborazione. La classe [CleanupOptions](https://apiference.aspose.com/words/java/com.aspose.words/CleanupOptions) consente di specificare le opzioni per la pulizia dei dotmumenti. Per rimuovere dal dotmumento stili duplicati o semplicemente stili o elenchi inutilizzati, puoi utilizzare il metodo [Cleanup](https://apiference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup()). È possibile utilizzare [UnusedStyles](https://apiference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://apiference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) per rilevare e rimuovere gli stili contrassegnati come "non utilizzati".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Rimuovere le informazioni inutilizzate da un dotmumento DOTM tramite Java" %}}
Dopo aver convertito DOTM in FODS, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) consente di salvare il dotmumento per lo streaming. Se è necessario salvare i file in uno Stream, è necessario creare un oggetto FileOutputStream e quindi [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) il file in quell'oggetto Stream chiamando il metodo di salvataggio di [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xlsm/" name="DOTM A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xlt/" name="DOTM A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-ods/" name="DOTM A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-tsv/" name="DOTM A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xls/" name="DOTM A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xlsb/" name="DOTM A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-fods/" name="DOTM A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-dif/" name="DOTM A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xltx/" name="DOTM A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xlam/" name="DOTM A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xlsx/" name="DOTM A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-xltm/" name="DOTM A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-sxc/" name="DOTM A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/dotm-to-excel/" name="DOTM A EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}