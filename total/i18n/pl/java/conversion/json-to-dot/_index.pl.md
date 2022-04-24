---
title: Konwertuj format JSON na DOT za pomocą Javy
description: Przetwarzaj JSON do DOT w Javie bez użycia Microsoft Word
url: /pl/java/conversion/json-to-dot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOT
otherformats: RTF FLATOPC ODT DOTX WORDML PCL DOC EPUB OTT WORD PS MOBI DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na DOT za pomocą Javy" h2="Lokalny interfejs Java API do przetwarzania JSON na DOT bez użycia Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz przekonwertować JSON na DOT w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/) możesz przetworzyć JSON na PDF. W drugim kroku możesz przekonwertować plik PDF na DOT za pomocą interfejsu API przetwarzania tekstu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DOT przez Javę" %}}
1. Utwórz nowy obiekt [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zaimportuj plik JSON do arkusza roboczego za pomocą klasy [JsonUtility](https://apireference.aspose.com/cells/java/com.aspose.cells/JsonUtility) i [Save](https://apireference.aspose.com/ cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) to jako PDF
3. Załaduj dokument PDF za pomocą klasy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie DOT za pomocą [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Ponadto interfejs API umożliwia ustawienie opcji układu dla JSON podczas analizowania JSON do DOT przy użyciu [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umożliwia przetwarzanie tablicy jako tabeli, ignorowanie wartości null, ignorowanie tytułu tablicy, ignorowanie tytułu obiektu, konwersję ciągu na liczbę lub datę, ustawianie formatu daty i liczby oraz ustawianie stylu tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na DOT za pomocą Java" %}}
Korzystając z API, możesz również przetworzyć JSON na DOT ze znakiem wodnym. Aby dodać znak wodny do dokumentu DOT, możesz najpierw przekonwertować plik JSON na PDF i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik PDF za pomocą klasy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), utwórz instancję TextWatermarkOptions i ustaw jego właściwości, wywołaj metodę Watermark.setText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions. Po dodaniu znaku wodnego możesz zapisać dokument w DOT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-flatopc/" name="JSON W celu FLAW celuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-docm/" name="JSON W celu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-word/" name="JSON W celu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-wordml/" name="JSON W celu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-odt/" name="JSON W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-rtf/" name="JSON W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-doc/" name="JSON W celu DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-mobi/" name="JSON W celu MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-ott/" name="JSON W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-dotx/" name="JSON W celu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-pcl/" name="JSON W celu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-dot/" name="JSON W celu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-epub/" name="JSON W celu EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/json-to-ps/" name="JSON W celu PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}