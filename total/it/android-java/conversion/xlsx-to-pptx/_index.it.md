---
title: Esporta XLSX in PPTX in Android
description: API Android per convertire XLSX in PPTX senza utilizzare Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: WORD POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi XLSX in PPTX su Android tramite Java" h2="Trasforma XLSX in PPTX all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) è un pacchetto di potenti API di automazione dei file. Utilizzando due delle sue API, puoi integrare la funzione di conversione da XLSX a PPTX all'interno delle tue applicazioni Android. Nel primo passaggio puoi esportare XLSX in PDF utilizzando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Successivamente, utilizzando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), puoi convertire PDF in PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare XLSX in PPTX" %}}
1. Aprire il file XLSX utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converti XLSX in PDF e imposta SaveFormat su AUTO
3. Caricare il file PDF convertito utilizzando la classe [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Salvare il pptxumento in formato PPTX utilizzando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total for Android via Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovi le proprietà personalizzate dal file XLSX in Android tramite Java" %}}
Oltre alla conversione dei pptxumenti, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) offre anche tantissime altre funzionalità. Prima del processo di conversione, puoi rimuovere le proprietà personalizzate del pptxumento XLSX. Per rimuovere le proprietà personalizzate, chiama il metodo [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) e passa il nome di la proprietà del pptxumento da rimuovere.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsx-to-word/" name="XLSX Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsx-to-powerpoint/" name="XLSX Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsx-to-pptxx/" name="XLSX Per PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsx-to-pptx/" name="XLSX Per PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}