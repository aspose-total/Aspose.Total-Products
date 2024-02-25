---
title: Converti EPUB in TXT in Android tramite Java
description: Esegui il rendering da EPUB a TXT in Android tramite API Java senza utilizzare Microsoft Excel o Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: TXT
otherformats: SXC XLAM ODS FODS TSV MD XLSB XLTX EXCEL DIF XLSM XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendering da EPUB a TXT in Android tramite Java" h2="Trasforma EPUB in TXT all'interno di applicazioni Android senza richiedere Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi integrare la funzione di conversione da EPUB a TXT all'interno delle tue applicazioni Android in un processo in due fasi. In primo luogo, utilizzando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) puoi convertire EPUB in XLSX. In secondo luogo, puoi convertire XLSX in TXT utilizzando la potente API di elaborazione dei fogli di calcolo [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Entrambe le API rientrano nella famiglia di prodotti [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per il rendering da EPUB a TXT" %}}
1. Aprire il file EPUB utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti EPUB in XLSX utilizzando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metodo
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato TXT utilizzando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://releases.aspose.com/total/java/) e installa [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni metadati XMP del file EPUB in Android tramite Java" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) consente di accedere ai metadati XMP di un file EPUB. Per ottenere i metadati, creare un oggetto [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e aprire il file EPUB di input e utilizzare [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) per ottenere i metadati.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Proteggi il documento TXT in Android tramite Java" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) supporta la protezione del file TXT in base alle tue esigenze. Per proteggere il tuo documento puoi utilizzare il metodo [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) di [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-txt.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}