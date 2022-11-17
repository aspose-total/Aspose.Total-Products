---
title: Konwertuj format JSON na DOTX w Androidzie przez Java
description: Przetwarzaj JSON do DOTX w Javie bez użycia Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOTX
otherformats: ODT DOCM DOT RTF PCL FLATOPC CHM OTT WORDML WORD DOC EPUB MOBI PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj format JSON na DOTX w aplikacjach na Androida" h2="Przetwarzaj JSON do DOTX w aplikacjach na Androida bez użycia Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować JSON na DOTX w swoich aplikacjach na Androida w dwuetapowym procesie. Po pierwsze, korzystając z interfejsu API Powerful Spreadsheet Processing [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) możesz przetworzyć JSON do formatu PDF. W drugim kroku możesz przekonwertować plik PDF na DOTX za pomocą interfejsu API przetwarzania tekstu [Aspose.Words na Androida przez Javę](https://products.aspose.com/words/android-java/). Oba interfejsy API należą do rodziny produktów [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DOTX w Androidzie przez Java" %}}
1. Utwórz nowy obiekt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zaimportuj plik JSON do arkusza roboczego za pomocą klasy [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) i [Save](https://reference.aspose.com/cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) to jako PDF
3. Załaduj dokument PDF za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie DOTX za pomocą [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj biblioteki w swojej aplikacji.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na DOTX w Androidzie przez Java" %}}
Ponadto interfejs API umożliwia ustawienie opcji układu dla formatu JSON podczas analizowania JSON do DOTX przy użyciu [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umożliwia przetwarzanie tablicy jako tabeli, ignorowanie wartości null, ignorowanie tytułu tablicy, ignorowanie tytułu obiektu, konwersję ciągu na liczbę lub datę, ustawianie formatu daty i liczby oraz ustawianie stylu tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj format JSON na DOTX ze znakiem wodnym w Androidzie za pomocą Java" %}}
Korzystając z API, możesz również przekonwertować JSON na DOTX ze znakiem wodnym. Aby dodać znak wodny do dokumentu DOTX, możesz najpierw przeanalizować plik JSON do formatu PDF i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik PDF za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), utwórz instancję TextWatermarkOptions i ustaw jego właściwości, Wywołaj metodę Watermark.setText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions. Po dodaniu znaku wodnego możesz zapisać dokument w DOTX.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-odt/" name="JSON Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-docm/" name="JSON Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-dot/" name="JSON Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-rtf/" name="JSON Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-pcl/" name="JSON Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-flatopc/" name="JSON Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-dotx/" name="JSON Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-ott/" name="JSON Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-wordml/" name="JSON Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-word/" name="JSON Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-doc/" name="JSON Do DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-epub/" name="JSON Do EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-mobi/" name="JSON Do MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/json-to-ps/" name="JSON Do PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}