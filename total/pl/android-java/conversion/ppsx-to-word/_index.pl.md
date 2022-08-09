---
title: Eksportuj PPSX do WORD na Androidzie przez Javę
description: Konwertuj PPSX na WORD w aplikacjach mobilnych bez instalowania żadnego oprogramowania
url: /pl/android-java/conversion/ppsx-to-word/
family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOCX
otherformats: DOC DOCX DOT DOCM FLATOPC WORDML RTF DOTM ODT DOTX TEXT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj PPSX do WORD na Androidzie przez Javę" h2="Interfejsy API formatów plików do konwersji PPSX na WORD w aplikacjach na Androida bez konieczności korzystania z programu Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) umożliwia manipulowanie formatami plików w aplikacjach na Androida. Korzystając z interfejsów API dostarczonych w pakiecie, możesz zautomatyzować proces konwersji PowerPoint PPSX do Word WORD w swoich aplikacjach.
Możesz przekonwertować swój dokument w dwóch krokach. Do renderowania PPSX do HTML możesz użyć [Aspose.Slides for Andorid przez Javę](https://products.aspose.com/slides/android-java/), czyli interfejsu API PowerPoint dla aplikacji na Androida. Następnie za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words dla Androida przez Javę](https://products.aspose.com/words/android-java/) możesz przekonwertować HTML na WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderowanie PPSX do WORD w systemie Android" %}}
1. Otwórz plik PPSX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj PPSX na HTML, używając [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) i ustaw HTML jako SaveFormat
3. Załaduj przekonwertowany plik HTML za pomocą klasy [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
4. Zapisz dokument w formacie WORD za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) i ustaw Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.Slides na Androida przez Javę](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) i [Aspose.Words na Androida przez Javę](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoim Aplikacje.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-word/" name="PPSX Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-wordx/" name="PPSX Do WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-dot/" name="PPSX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-wordm/" name="PPSX Do WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-flatopc/" name="PPSX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-wordml/" name="PPSX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-rtf/" name="PPSX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-dotm/" name="PPSX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-odt/" name="PPSX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-dotx/" name="PPSX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-text/" name="PPSX Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppsx-to-ott/" name="PPSX Do OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}