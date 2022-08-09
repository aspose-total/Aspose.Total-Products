---
title: Esporta XLSM in POWERPOINT in Android
description: API Android per convertire XLSM in POWERPOINT senza utilizzare Microsoft Word
url: /it/android-java/conversion/xlsm-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: PPTX WORD DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi XLSM in POWERPOINT su Android tramite Java" h2="Trasforma XLSM in POWERPOINT all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total per Android tramite Java](https://products.aspose.com/total/android-java/) è un pacchetto di potenti API di automazione dei file. Utilizzando due delle sue API, puoi integrare la funzione di conversione da XLSM a POWERPOINT all'interno delle tue applicazioni Android. Nel primo passaggio puoi esportare XLSM in PDF utilizzando [Aspose.Cells per Android tramite Java](https://products.aspose.com/cells/android-java/). Successivamente, utilizzando [Aspose.PDF per Android tramite Java](https://products.aspose.com/pdf/android-java/), puoi convertire PDF in POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare XLSM in POWERPOINT" %}}
1. Aprire il file XLSM utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converti XLSM in PDF e imposta SaveFormat su AUTO
3. Caricare il file PDF convertito utilizzando la classe [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Salvare il powerpointumento in formato POWERPOINT utilizzando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF per Android tramite Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells per Android tramite Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovi le proprietà personalizzate dal file XLSM in Android tramite Java" %}}
Oltre alla conversione dei powerpointumenti, [Aspose.Cells per Android tramite Java](https://products.aspose.com/cells/android-java/) offre anche tantissime altre funzionalità. Prima del processo di conversione, puoi rimuovere le proprietà personalizzate del powerpointumento XLSM. Per rimuovere le proprietà personalizzate, chiama il metodo [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) e passa il nome di la proprietà del powerpointumento da rimuovere.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-pptx/" name="XLSM Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-word/" name="XLSM Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-powerpointx/" name="XLSM Per POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-powerpoint/" name="XLSM Per POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}