---
title: Konwertuj format JSON na RTF za pomocą Javy
description: Przetwarzaj JSON do RTF w Javie bez użycia Microsoft Word
url_ignore: /pl/java/conversion/json-to-rtf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: RTF
otherformats: EPUB FLATOPC PCL WORDML DOTX PS DOCM RTF DOC WORD MOBI ODT DOT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na RTF za pomocą Javy" h2="Lokalny interfejs Java API do przetwarzania JSON na RTF bez użycia Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz przekonwertować JSON na RTF w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/) możesz przetworzyć JSON na PDF. W drugim kroku możesz przekonwertować plik PDF na RTF za pomocą interfejsu API przetwarzania tekstu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na RTF przez Javę" %}}
1. Utwórz nowy obiekt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zaimportuj plik JSON do arkusza roboczego za pomocą klasy [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) i [Save](https://reference.aspose.com/ cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) to jako PDF
3. Załaduj dokument PDF za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Zapisz dokument w formacie RTF za pomocą [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Ponadto interfejs API umożliwia ustawienie opcji układu dla JSON podczas analizowania JSON do RTF przy użyciu [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umożliwia przetwarzanie tablicy jako tabeli, ignorowanie wartości null, ignorowanie tytułu tablicy, ignorowanie tytułu obiektu, konwersję ciągu na liczbę lub datę, ustawianie formatu daty i liczby oraz ustawianie stylu tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na RTF za pomocą Java" %}}
Korzystając z API, możesz również przetworzyć JSON na RTF ze znakiem wodnym. Aby dodać znak wodny do dokumentu RTF, możesz najpierw przekonwertować plik JSON na PDF i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik PDF za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), utwórz instancję TextWatermarkOptions i ustaw jego właściwości, wywołaj metodę Watermark.setText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions. Po dodaniu znaku wodnego możesz zapisać dokument w RTF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}