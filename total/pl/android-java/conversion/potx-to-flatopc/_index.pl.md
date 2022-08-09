---
title: Eksportuj POTX do FLATOPC na Androidzie przez Javę
description: Konwertuj POTX na FLATOPC w aplikacjach mobilnych bez instalowania żadnego oprogramowania
url: /pl/android-java/conversion/potx-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: FLATOPC
otherformats: ODT TEXT WORDML DOCX DOTM DOC DOT RTF WORD DOCM OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj POTX do FLATOPC na Androidzie przez Javę" h2="Interfejsy API formatów plików do konwersji POTX na FLATOPC w aplikacjach na Androida bez konieczności korzystania z programu Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) umożliwia manipulowanie formatami plików w aplikacjach na Androida. Korzystając z interfejsów API dostarczonych w pakiecie, możesz zautomatyzować proces konwersji PowerPoint POTX do Word FLATOPC w swoich aplikacjach.
Możesz przekonwertować swój dokument w dwóch krokach. Do renderowania POTX do HTML możesz użyć [Aspose.Slides for Andorid przez Javę](https://products.aspose.com/slides/android-java/), czyli interfejsu API PowerPoint dla aplikacji na Androida. Następnie za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words dla Androida przez Javę](https://products.aspose.com/words/android-java/) możesz przekonwertować HTML na FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderowanie POTX do FLATOPC w systemie Android" %}}
1. Otwórz plik POTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj POTX na HTML, używając [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) i ustaw HTML jako SaveFormat
3. Załaduj przekonwertowany plik HTML za pomocą klasy [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)
4. Zapisz dokument w formacie FLATOPC za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int)) i ustaw Flatopc jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.Slides na Androida przez Javę](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) i [Aspose.Words na Androida przez Javę](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoim Aplikacje.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-odt/" name="POTX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-text/" name="POTX Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-wordml/" name="POTX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-flatopcx/" name="POTX Do FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-dotm/" name="POTX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-flatopc/" name="POTX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-dot/" name="POTX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-rtf/" name="POTX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-word/" name="POTX Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-flatopcm/" name="POTX Do FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-ott/" name="POTX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/potx-to-dotx/" name="POTX Do DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}