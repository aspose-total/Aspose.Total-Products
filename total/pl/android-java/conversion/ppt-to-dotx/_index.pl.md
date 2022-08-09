---
title: Eksportuj PPT do DOTX na Androidzie przez Javę
description: Konwertuj PPT na DOTX w aplikacjach mobilnych bez instalowania żadnego oprogramowania
url: /pl/android-java/conversion/ppt-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOTX
otherformats: OTT TEXT FLATOPC DOT WORD DOTM ODT DOCM DOCX RTF DOC WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj PPT do DOTX na Androidzie przez Javę" h2="Interfejsy API formatów plików do konwersji PPT na DOTX w aplikacjach na Androida bez konieczności korzystania z programu Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) umożliwia manipulowanie formatami plików w aplikacjach na Androida. Korzystając z interfejsów API dostarczonych w pakiecie, możesz zautomatyzować proces konwersji PowerPoint PPT do Word DOTX w swoich aplikacjach.
Możesz przekonwertować swój dokument w dwóch krokach. Do renderowania PPT do HTML możesz użyć [Aspose.Slides for Andorid przez Javę](https://products.aspose.com/slides/android-java/), czyli interfejsu API PowerPoint dla aplikacji na Androida. Następnie za pomocą interfejsu API przetwarzania dokumentów [Aspose.Words dla Androida przez Javę](https://products.aspose.com/words/android-java/) możesz przekonwertować HTML na DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Renderowanie PPT do DOTX w systemie Android" %}}
1. Otwórz plik PPT za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj PPT na HTML, używając [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) i ustaw HTML jako SaveFormat
3. Załaduj przekonwertowany plik HTML za pomocą klasy [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
4. Zapisz dokument w formacie DOTX za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) i ustaw Dotx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.Slides na Androida przez Javę](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) i [Aspose.Words na Androida przez Javę](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) w swoim Aplikacje.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-ott/" name="PPT Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-text/" name="PPT Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-flatopc/" name="PPT Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-dot/" name="PPT Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-word/" name="PPT Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-dotm/" name="PPT Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-odt/" name="PPT Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-dotxm/" name="PPT Do DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-dotxx/" name="PPT Do DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-rtf/" name="PPT Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-dotx/" name="PPT Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/ppt-to-wordml/" name="PPT Do WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}