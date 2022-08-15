---
title: Konwertuj format JSON na DOTX za pomocą C++
description: C++ API t0 Parsowanie JSON do DOTX bez użycia Microsoft Word
url: /pl/cpp/conversion/json-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOC MOBI DOT ODT WORD WORDML FLATOPC PS CHM PCL OTT EPUB DOCM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj format JSON na DOTX za pomocą C++" h2="Przetwarzaj JSON do DOTX w aplikacjach C++ bez użycia Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for C++](https://products.aspose.com/total/cpp/) możesz przeanalizować JSON do DOTX w swoich aplikacjach C++ w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), możesz wyeksportować JSON do formatu PDF. Następnie, używając [Aspose.Words for C++](https://products.aspose.com/words/cppp/), możesz przekonwertować PDF na DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DOTX w C++" %}}
1. Utwórz nowy obiekt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zapisz JSON jako PDF przy użyciu metody [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Załaduj dokument PDF za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Zapisz dokument w formacie DOTX za pomocą metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na DOTX w C++" %}}
Podczas analizowania JSON do DOTX możesz również ustawić rozmiar wierszy i kolumn, ładując JSON za pomocą klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Jeśli chcesz ustawić tę samą wysokość wiersza dla wszystkich wierszy w arkuszu, możesz to zrobić za pomocą [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metoda kolekcji [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Podobnie, aby ustawić tę samą szerokość kolumny dla wszystkich kolumn w arkuszu, użyj metody [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) kolekcji ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj format JSON na DOTX za pomocą znaku wodnego w C++" %}}
Korzystając z API, możesz również przetworzyć JSON na DOTX ze znakiem wodnym. Aby dodać znak wodny do dokumentu DOTX, możesz najpierw przekonwertować JSON na PDF i dodać do niego znak wodny. Aby dodać znak wodny, wczytaj nowo utworzony plik PDF za pomocą klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), ustaw różne właściwości dla tekstowego znaku wodnego,
wywołaj metodę SetText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions. Po dodaniu znaku wodnego możesz zapisać dokument w DOTX.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-doc/" name="JSON Do DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-mobi/" name="JSON Do MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-dot/" name="JSON Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-odt/" name="JSON Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-word/" name="JSON Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-wordml/" name="JSON Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-flatopc/" name="JSON Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-ps/" name="JSON Do PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-dotx/" name="JSON Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-pcl/" name="JSON Do PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-ott/" name="JSON Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-epub/" name="JSON Do EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-docm/" name="JSON Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/json-to-rtf/" name="JSON Do RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}