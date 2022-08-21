---
title: Eksportuj TSV do PPTX w Androidzie
description: Android API do konwersji TSV na PPTX bez użycia Microsoft Word
url: /pl/android-java/conversion/tsv-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: PPTX
otherformats: DOCX POWERPOINT WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj TSV do PPTX na Androidzie przez Javę" h2="Przekształć TSV w PPTX w swoich aplikacjach na Androida bez użycia Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) to pakiet zaawansowanych interfejsów API automatyzacji plików. Korzystając z dwóch jego interfejsów API, możesz zintegrować funkcję konwersji TSV na PPTX w swoich aplikacjach na Androida. W pierwszym kroku możesz wyeksportować plik TSV do pliku PDF, używając [Aspose.Cells na Androida przez Javę](https://products.aspose.com/cells/android-java/). Następnie, używając [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), możesz przekonwertować PDF na PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API do eksportu TSV do PPTX" %}}
1. Otwórz plik TSV za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konwertuj TSV na PDF i ustaw SaveFormat na AUTO
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Zapisz dokument w formacie PPTX za pomocą [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.PDF na Androida przez Javę](https://pptxs.aspose.com/pdf/androidjava/installation/) i [Aspose.Cells na Androida przez Javę](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Usuń niestandardowe właściwości z pliku TSV w Androidzie za pomocą Java" %}}
Oprócz konwersji dokumentów [Aspose.Cells na Androida przez Javę](https://products.aspose.com/cells/android-java/) zapewnia również mnóstwo innych funkcji. Przed procesem konwersji możesz usunąć niestandardowe właściwości dokumentu TSV. Aby usunąć właściwości niestandardowe, wywołaj metodę [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) i przekaż nazwę właściwość dokumentu do usunięcia.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/tsv-to-pptxx/" name="TSV Do PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/tsv-to-powerpoint/" name="TSV Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/tsv-to-word/" name="TSV Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/tsv-to-pptx/" name="TSV Do PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}