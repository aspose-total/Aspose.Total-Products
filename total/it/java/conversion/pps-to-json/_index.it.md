---
title: Converti PPS in formato JSON tramite Java
description: Converti il formato PPS in JSON tramite Java senza utilizzare Microsoft Excel o PowerPoint
url_ignore: /it/java/conversion/pps-to-json/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti PPS in formato JSON tramite Java" h2="API Java in loco per esportare PPS in JSON senza utilizzare Microsoft<sup>&reg;</sup> Excel o PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversione del formato PPS in formato JSON tramite [Aspose.Total for Java](https://products.aspose.com/total/java/) è un semplice processo in due fasi. Nel primo passaggio puoi esportare PPS in HTML utilizzando [Aspose.Slides for Java](https://products.aspose.com/slides/java/). In secondo luogo, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi convertire HTML in JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti PPS in formato JSON tramite Java" %}}
1. Aprire il file PPS utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converti PPS in HTML utilizzando [save](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. ISaveOptions-) metodo
3. Caricare il documento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salvare il documento in formato JSON utilizzando [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Utilizzando l'API, puoi anche aprire il documento protetto da password. Se il documento PPS di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il documento crittografato passando la password corretta in un oggetto LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti PPS protetto in formato JSON tramite Java" %}}
Durante la conversione da PPS a JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, creare un intervallo di dati da esportare utilizzando il metodo Cells.createRange, chiamare il metodo JsonUtility.exportRangeToJson con i riferimenti di Range & ExportRangeToJsonOptions e scrivere i dati JSON della stringa su file tramite BufferedWriter.write metodo. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}