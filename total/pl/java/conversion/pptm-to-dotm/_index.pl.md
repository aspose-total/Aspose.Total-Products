---
title: Konwertuj PPTM na DOTM przez Javę
description: Java API do eksportu PPTM do DOTM bez użycia Microsoft Word lub PowerPoint
url_ignore: /pl/java/conversion/pptm-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: DOTM
otherformats: DOTMX DOTMM FLATOPC DOTM TEXT WORDML OTT DOT WORD ODT RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj PPTM na DOTM przez Java" h2="On Premise Java API do konwersji PowerPoint PPTM do DOTM w dowolnych aplikacjach Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Biblioteki File Format Automation umożliwiają programistom Java automatyzację procesu konwersji wsadowej PowerPoint PPTM do Word DOTM. Konwersja dokumentu jest procesem dwuetapowym i obejmuje użycie dwóch interfejsów API. Aby przekonwertować PPTM na HTML, użyjemy [Aspose.Slides for Java](https://products.aspose.com/slides/java/), czyli interfejsu API programu PowerPoint do manipulowania prezentacjami i zarządzania nimi. Następnie za pomocą bogatego w funkcje interfejsu API przetwarzania tekstu [Aspose.Words for Java](https://products.aspose.com/words/java/) przekonwertujemy kod HTML na DOTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować PPTM na DOTM za pomocą Javy?" %}}
1. Otwórz plik PPTM za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj PPTM na HTML, używając [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) i ustaw HTML jako SaveFormat
3. Załaduj przekonwertowany plik HTML za pomocą klasy [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
4. Zapisz dokument w formacie DOTM za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Do konwersji plików PPTM do DOTM można łatwo użyć Aspose.Total dla Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Korzystając z API, możesz również wykonać konwersję pliku PPTM do DOTM ze znakiem wodnym. Aby dodać znak wodny do dokumentu DOTM, możesz najpierw przekonwertować plik PPTM na HTML i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik HTML za pomocą klasy [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument), utwórz instancję TextWatermarkOptions i ustaw jego właściwości, wywołaj metodę Watermark.setText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-word/" name="PPTM W celu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-dotx/" name="PPTM W celu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-odt/" name="PPTM W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-ott/" name="PPTM W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-rtf/" name="PPTM W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-flatopc/" name="PPTM W celu FLAW celuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-wordml/" name="PPTM W celu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-dotmm/" name="PPTM W celu DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-text/" name="PPTM W celu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-dotmx/" name="PPTM W celu DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-dotm/" name="PPTM W celu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptm-to-dot/" name="PPTM W celu DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}