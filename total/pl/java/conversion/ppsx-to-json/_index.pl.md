---
title: Konwertuj PPSX na format JSON przez Java
description: Konwertuj PPSX do formatu JSON przez Javę bez używania Microsoft Excel lub PowerPoint
url_ignore: /pl/java/conversion/ppsx-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj PPSX na format JSON przez Java" h2="On Premise Java API do eksportowania PPSX do JSON bez użycia Microsoft<sup>&reg;</sup> Excel lub PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja PPSX do formatu JSON za pomocą [Aspose.Total for Java](https://products.aspose.com/total/java/) to prosty, dwuetapowy proces. W pierwszym kroku możesz wyeksportować PPSX do HTML za pomocą [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Po drugie, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przekonwertować HTML na JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj PPSX na format JSON przez Java" %}}
1. Otwórz plik PPSX za pomocą klasy [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Przekonwertuj PPSX na HTML, używając [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Metoda ISaveOptions-)
3. Załaduj dokument HTML za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie JSON za pomocą [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Korzystając z interfejsu API, możesz również otworzyć dokument chroniony hasłem. Jeśli wejściowy dokument PPSX jest chroniony hasłem, nie można go przekonwertować na format JSON bez użycia hasła. API umożliwia otwarcie zaszyfrowanego dokumentu poprzez podanie prawidłowego hasła w obiekcie LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik PPSX na format JSON za pomocą Javy" %}}
Podczas konwertowania PPSX na JSON możesz również ustawić zakres na wyjściowy format JSON. Aby ustawić zakres, możesz otworzyć przekonwertowany kod HTML za pomocą klasy Workbook, utworzyć zakres danych do wyeksportowania za pomocą metody Cells.createRange, wywołać metodę JsonUtility.exportRangeToJson z odwołaniami do Range & ExportRangeToJsonOptions i zapisać ciąg danych JSON do pliku za pomocą Metoda BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-doc/" name="PPSX W celu DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-docm/" name="PPSX W celu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-docx/" name="PPSX W celu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-dot/" name="PPSX W celu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-dotm/" name="PPSX W celu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-dotx/" name="PPSX W celu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-odt/" name="PPSX W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-ott/" name="PPSX W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-rtf/" name="PPSX W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-text/" name="PPSX W celu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-word/" name="PPSX W celu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ppsx-to-wordml/" name="PPSX W celu WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}