---
title: Eksportuj XLSB do WORD w Androidzie
description: Android API do konwersji XLSB na WORD bez użycia Microsoft Word
url: /pl/android-java/conversion/xlsb-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: DOC
otherformats: DOC PPTX DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj XLSB do WORD na Androidzie przez Javę" h2="Przekształć XLSB w WORD w swoich aplikacjach na Androida bez użycia Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) to pakiet zaawansowanych interfejsów API automatyzacji plików. Korzystając z dwóch jego interfejsów API, możesz zintegrować funkcję konwersji XLSB na WORD w swoich aplikacjach na Androida. W pierwszym kroku możesz wyeksportować plik XLSB do pliku PDF, używając [Aspose.Cells na Androida przez Javę](https://products.aspose.com/cells/android-java/). Następnie, używając [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), możesz przekonwertować PDF na WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API do eksportu XLSB do WORD" %}}
1. Otwórz plik XLSB za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konwertuj XLSB na PDF i ustaw SaveFormat na AUTO
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Zapisz dokument w formacie WORD za pomocą [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.PDF na Androida przez Javę](https://words.aspose.com/pdf/androidjava/installation/) i [Aspose.Cells na Androida przez Javę](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Usuń niestandardowe właściwości z pliku XLSB w Androidzie za pomocą Java" %}}
Oprócz konwersji dokumentów [Aspose.Cells na Androida przez Javę](https://products.aspose.com/cells/android-java/) zapewnia również mnóstwo innych funkcji. Przed procesem konwersji możesz usunąć niestandardowe właściwości dokumentu XLSB. Aby usunąć właściwości niestandardowe, wywołaj metodę [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) i przekaż nazwę właściwość dokumentu do usunięcia.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xlsb-to-word/" name="XLSB Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xlsb-to-pptx/" name="XLSB Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xlsb-to-wordx/" name="XLSB Do WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/xlsb-to-powerpoint/" name="XLSB Do POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}