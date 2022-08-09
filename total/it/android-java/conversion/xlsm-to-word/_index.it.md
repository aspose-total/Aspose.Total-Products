---
title: Esporta XLSM in WORD in Android
description: API Android per convertire XLSM in WORD senza utilizzare Microsoft Word
url: /it/android-java/conversion/xlsm-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: PPTX DOCX DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendi XLSM in WORD su Android tramite Java" h2="Trasforma XLSM in WORD all'interno delle tue applicazioni Android senza utilizzare Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total per Android tramite Java](https://products.aspose.com/total/android-java/) è un pacchetto di potenti API di automazione dei file. Utilizzando due delle sue API, puoi integrare la funzione di conversione da XLSM a WORD all'interno delle tue applicazioni Android. Nel primo passaggio puoi esportare XLSM in PDF utilizzando [Aspose.Cells per Android tramite Java](https://products.aspose.com/cells/android-java/). Successivamente, utilizzando [Aspose.PDF per Android tramite Java](https://products.aspose.com/pdf/android-java/), puoi convertire PDF in WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android per esportare XLSM in WORD" %}}
1. Aprire il file XLSM utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converti XLSM in PDF e imposta SaveFormat su AUTO
3. Caricare il file PDF convertito utilizzando la classe [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Salvare il wordumento in formato WORD utilizzando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Android tramite Java direttamente da [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e installa [Aspose.PDF per Android tramite Java](https://words.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells per Android tramite Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) nelle tue applicazioni.

In alternativa, puoi ottenere un file ZIP da [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Rimuovi le proprietà personalizzate dal file XLSM in Android tramite Java" %}}
Oltre alla conversione dei wordumenti, [Aspose.Cells per Android tramite Java](https://products.aspose.com/cells/android-java/) offre anche tantissime altre funzionalità. Prima del processo di conversione, puoi rimuovere le proprietà personalizzate del wordumento XLSM. Per rimuovere le proprietà personalizzate, chiama il metodo [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) e passa il nome di la proprietà del wordumento da rimuovere.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-pptx/" name="XLSM Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-wordx/" name="XLSM Per WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-word/" name="XLSM Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/android-java/conversion/xlsm-to-powerpoint/" name="XLSM Per POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}