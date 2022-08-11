---
title: Konwertuj WORD na SXC w C++
description: C++ API do konwersji WORD na SXC bez używania Microsoft Word lub Microsoft Excel
url: /pl/cpp/conversion/word-to-sxc/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: SXC
otherformats: XLSM XLT XLSX ODS XLAM EXCEL DIF CSV TSV XLTM XLSB XLS XLTX FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do konwersji WORD na SXC" h2="Eksportuj WORD do SXC za pomocą C++ bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz łatwo włączyć funkcję konwersji WORD do SXC w swoich aplikacjach C++. Korzystając z bogatego w funkcje, wydajnego i łatwego w użyciu interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz eksportować WORD do HTML. Następnie, używając [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), możesz przekonwertować HTML na SXC. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji WORD na SXC" %}}
1. Otwórz plik WORD, korzystając z odwołania do klasy [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument)
2. Konwertuj WORD na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat)
3. Załaduj dokument HTML, używając odwołania do klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Zapisz dokument w formacie SXC za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj dostęp do właściwości dokumentu WORD za pomocą C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) umożliwia również dostęp do właściwości dokumentu pliku WORD i pozwala podjąć świadomą decyzję przed procesem konwersji. Aby uzyskać dostęp do właściwości dokumentu, możesz użyć [BuiltInWordumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordument_properties), aby uzyskać wbudowane właściwości i [CustomWordumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_wordument_properties), aby uzyskać właściwości niestandardowe. Poniższy przykład kodu pokazuje, jak wyliczyć wszystkie wbudowane i niestandardowe właściwości w dokumencie.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Zapisz plik SXC w strumieniu za pomocą C++" %}}
Po przekonwertowaniu WORD na SXC [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Aby zapisać pliki w strumieniu, utwórz obiekt MemoryStream lub FileStream i zapisz plik w tym obiekcie strumienia, wywołując [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metoda obiektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Określ żądany format pliku, używając wyliczenia [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) podczas wywoływania [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xlsm/" name="WORD Do XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xlt/" name="WORD Do XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xlsx/" name="WORD Do XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-ods/" name="WORD Do ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xlam/" name="WORD Do XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-excel/" name="WORD Do EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-dif/" name="WORD Do DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-sxc/" name="WORD Do SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-tsv/" name="WORD Do TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xltm/" name="WORD Do XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xlsb/" name="WORD Do XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xls/" name="WORD Do XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-xltx/" name="WORD Do XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/word-to-fods/" name="WORD Do FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}