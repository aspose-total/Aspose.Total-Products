---
title: Konwertuj POTM na DOC przez Javę
description: Java API do eksportu POTM do DOC bez użycia Microsoft Word lub PowerPoint
url_ignore: /pl/java/conversion/potm-to-doc/
family: total
platformtag: net
feature: conversion
informat: POTMM
outformat: DOC
otherformats: WORDML DOCX OTT ODT FLATOPC DOTM DOTX DOT DOCM RTF TEXT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj POTM na DOC przez Java" h2="On Premise Java API do konwersji PowerPoint POTM do DOC w dowolnych aplikacjach Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Biblioteki File Format Automation umożliwiają programistom Java automatyzację procesu konwersji wsadowej PowerPoint POTM do Word DOC. Konwersja dokumentu jest procesem dwuetapowym i obejmuje użycie dwóch interfejsów API. Aby przekonwertować POTM na HTML, użyjemy [Aspose.Slides for Java](https://products.aspose.com/slides/java/), czyli interfejsu API programu PowerPoint do manipulowania prezentacjami i zarządzania nimi. Następnie za pomocą bogatego w funkcje interfejsu API przetwarzania tekstu [Aspose.Words for Java](https://products.aspose.com/words/java/) przekonwertujemy kod HTML na DOC.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować POTM na DOC za pomocą Javy?" %}}
1. Otwórz plik POTM za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj POTM na HTML, używając [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) i ustaw HTML jako SaveFormat
3. Załaduj przekonwertowany plik HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie DOC za pomocą metody [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Do konwersji plików POTM do DOC można łatwo użyć Aspose.Total dla Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Korzystając z API, możesz również wykonać konwersję pliku POTM do DOC ze znakiem wodnym. Aby dodać znak wodny do dokumentu DOC, możesz najpierw przekonwertować plik POTM na HTML i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik HTML za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), utwórz instancję TextWatermarkOptions i ustaw jego właściwości, wywołaj metodę Watermark.setText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-word/" name="POTM W celu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-dotx/" name="POTM W celu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-odt/" name="POTM W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-ott/" name="POTM W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-rtf/" name="POTM W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-flatopc/" name="POTM W celu FLAW celuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-wordml/" name="POTM W celu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-docm/" name="POTM W celu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-text/" name="POTM W celu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-docx/" name="POTM W celu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-dotm/" name="POTM W celu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-dot/" name="POTM W celu DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}