---
title: API Java per convertire ODT in XLSB
description: Converti ODT in XLSB tramite Java senza utilizzare Microsoft Word o Microsoft Excel
url_ignore: /it/java/conversion/odt-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: XLSB
otherformats: XLSB TSV XLS EXCEL DIF XLSX FODS SXC XLT XLAM ODS XLSM XLTX XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti ODT in XLSB tramite Java" h2="API Java in loco per convertire ODT in XLSB senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione di ODT in XLSB tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) √® un semplice processo in due fasi. Utilizzando l'API di conversione e manipolazione dei documenti ricca di funzionalit√† [Aspose.Words per Java](https://products.aspose.com/words/java/), puoi esportare ODT in HTML. Successivamente, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire ODT in XLSB" %}}
1. Aprire il file ODT utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document)
2. Converti ODT in HTML utilizzando [Salva](https://apiference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metodo
3. Caricare il documento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato XLSB utilizzando [Salva](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includono [Aspose.Words per Java](https://docs.aspose.com/words/java/installation/) e [Aspose.Cells per Java](https://docs.aspose.com/cells/java/installation/) nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Prima di convertire ODT in XLSB, √® possibile rimuovere le informazioni non utilizzate dal documento ODT tramite [Aspose.Words for Java](https://products.aspose.com/words/java/). A volte potrebbe essere necessario rimuovere le informazioni non utilizzate o duplicate per ridurre le dimensioni del documento di output e il tempo di elaborazione. La classe [CleanupOptions](https://apiference.aspose.com/words/java/com.aspose.words/CleanupOptions) consente di specificare le opzioni per la pulizia dei documenti. Per rimuovere dal documento stili duplicati o semplicemente stili o elenchi inutilizzati, puoi utilizzare il metodo [Cleanup](https://apiference.aspose.com/words/java/com.aspose.words/Document#cleanup()). √ą possibile utilizzare [UnusedStyles](https://apiference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) e [UnusedBuiltinStyles](https://apiference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) per rilevare e rimuovere gli stili contrassegnati come "non utilizzati".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Rimuovere le informazioni inutilizzate da un documento ODT tramite Java" %}}
Dopo aver convertito ODT in XLSB, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) consente di salvare il documento per lo streaming. Se √® necessario salvare i file in uno Stream, √® necessario creare un oggetto FileOutputStream e quindi [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) il file in quell'oggetto Stream chiamando il metodo di salvataggio di [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xlsm/" name="ODT A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xlt/" name="ODT A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-ods/" name="ODT A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-tsv/" name="ODT A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xls/" name="ODT A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xlsb/" name="ODT A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-fods/" name="ODT A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-dif/" name="ODT A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xltx/" name="ODT A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xlam/" name="ODT A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xlsx/" name="ODT A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-xltm/" name="ODT A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-sxc/" name="ODT A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/odt-to-excel/" name="ODT A EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}