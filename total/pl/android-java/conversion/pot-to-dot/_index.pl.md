---
title: Eksportuj POT do DOT na Androidzie przez Javę
description: Konwertuj POT na DOT w aplikacjach mobilnych bez instalowania żadnego oprogramowania
url: /pl/android-java/conversion/pot-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOT
otherformats: DOCM DOCX OTT TEXT ODT WORDML DOC FLATOPC DOTM RTF WORD DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj POT do DOT na Androidzie przez Javę" h2="Interfejsy API formatów plików do konwersji POT na DOT w aplikacjach na Androida bez konieczności korzystania z programu Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) umożliwia manipulowanie formatami plików w aplikacjach na Androida. Korzystając z interfejsów API dostarczonych w pakiecie, możesz zautomatyzować proces konwersji PowerPoint POT do Word DOT w swoich aplikacjach.
Możesz przekonwertować swój dokument w dwóch krokach. Do renderowania POT do HTML możesz użyć [Aspose.Slides for Andorid przez Javę](https://products.aspose.com/slides/android-java/), czyli interfejsu API PowerPoint dla aplikacji na Androida. Następnie za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words dla Androida przez Javę](https://products.aspose.com/words/android-java/) możesz przekonwertować HTML na DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderowanie POT do DOT w systemie Android" %}}
1. Otwórz plik POT za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj POT na HTML, używając [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) i ustaw HTML jako SaveFormat
3. Załaduj przekonwertowany plik HTML za pomocą klasy [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
4. Zapisz dokument w formacie DOT za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,int)) i ustaw Dot jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.Slides na Androida przez Javę](https://dots.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) i [Aspose.Words na Androida przez Javę](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoim Aplikacje.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotument
Dotument dotument = new Dotument("htmlOutput.html");
// save dotument in DOT format
dotument.save("output.dot",SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-dotm/" name="POT Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-dotx/" name="POT Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-ott/" name="POT Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-text/" name="POT Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-odt/" name="POT Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-wordml/" name="POT Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-dot/" name="POT Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-flatopc/" name="POT Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-dotm/" name="POT Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-rtf/" name="POT Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-word/" name="POT Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/pot-to-dotx/" name="POT Do DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}