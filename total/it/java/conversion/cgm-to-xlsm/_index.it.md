---
title: API Java per il rendering da CGM a XLSM
description: Esporta CGM in XLSM tramite API Java senza utilizzare Microsoft Excel o Adobe Reader
url: /it/java/conversion/cgm-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSM
otherformats: FODS XLAM DIF SXC XLTM MD XLSM TSV EXCEL XLTX XLT ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta CGM in XLSM tramite Java" h2="Converti file CGM in XLSM utilizzando l'API Java in locale all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/) puoi integrare la funzione di conversione da CGM a XLSM nelle tue applicazioni Java in un processo in due fasi. In primo luogo, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) è possibile eseguire il rendering da CGM a XLSX. Nel secondo passaggio, puoi convertire XLSX in XLSM utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file CGM in XLSM tramite Java" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converti CGM in XLSX utilizzando [save](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metodo
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato XLSM utilizzando [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includere [Aspose.PDF per Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells per Java](https://docs.aspose.com/cells/java/ installazione/) nel tuo pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Se il tuo documento CGM è protetto da password, non puoi convertirlo in XLSM senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza di [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) e passare il nome del file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti CGM protetto in XLSM tramite Java" %}}
Durante la conversione del file CGM in XLSM, puoi anche aggiungere una filigrana al formato del file XLSM di output. Per aggiungere una filigrana, crea una nuova cartella di lavoro per aprire il file XLSX convertito. Seleziona Foglio di lavoro tramite il suo indice, crea una forma e usa la sua funzione addTextEffect, imposta colori, trasparenza e altro. Successivamente puoi salvare il tuo documento XLSX come XLSM con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-dif/" name="CGM A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xltx/" name="CGM A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-md/" name="CGM A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-fods/" name="CGM A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xltm/" name="CGM A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-excel/" name="CGM A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xlsm/" name="CGM A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xlam/" name="CGM A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xlt/" name="CGM A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-xlsb/" name="CGM A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-ods/" name="CGM A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/cgm-to-sxc/" name="CGM A SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}