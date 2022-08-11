---
title: Konwertuj DOTM na TSV w C++
description: C++ API do konwersji DOTM na TSV bez używania Microsoft Word lub Microsoft Excel
url: /pl/cpp/conversion/dotm-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: TSV
otherformats: XLAM XLSM XLS SXC FODS DIF XLTM XLSB EXCEL XLSX XLTX XLT ODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do konwersji DOTM na TSV" h2="Eksportuj DOTM do TSV za pomocą C++ bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz łatwo włączyć funkcję konwersji DOTM do TSV w swoich aplikacjach C++. Korzystając z bogatego w funkcje, wydajnego i łatwego w użyciu interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz eksportować DOTM do HTML. Następnie, używając [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), możesz przekonwertować HTML na TSV. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji DOTM na TSV" %}}
1. Otwórz plik DOTM, korzystając z odwołania do klasy [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
2. Konwertuj DOTM na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string_saveformat)
3. Załaduj dokument HTML, używając odwołania do klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Zapisz dokument w formacie TSV za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj dostęp do właściwości dokumentu DOTM za pomocą C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) umożliwia również dostęp do właściwości dokumentu pliku DOTM i pozwala podjąć świadomą decyzję przed procesem konwersji. Aby uzyskać dostęp do właściwości dokumentu, możesz użyć [BuiltInDotmumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotmument_properties), aby uzyskać wbudowane właściwości i [CustomDotmumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotmument_properties), aby uzyskać właściwości niestandardowe. Poniższy przykład kodu pokazuje, jak wyliczyć wszystkie wbudowane i niestandardowe właściwości w dokumencie.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotmument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Zapisz plik TSV w strumieniu za pomocą C++" %}}
Po przekonwertowaniu DOTM na TSV [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Aby zapisać pliki w strumieniu, utwórz obiekt MemoryStream lub FileStream i zapisz plik w tym obiekcie strumienia, wywołując [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metoda obiektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Określ żądany format pliku, używając wyliczenia [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) podczas wywoływania [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xlam/" name="DOTM Do XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xlsm/" name="DOTM Do XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xls/" name="DOTM Do XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-sxc/" name="DOTM Do SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-fods/" name="DOTM Do FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-dif/" name="DOTM Do DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xltm/" name="DOTM Do XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xlsb/" name="DOTM Do XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-excel/" name="DOTM Do EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xlsx/" name="DOTM Do XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xltx/" name="DOTM Do XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-xlt/" name="DOTM Do XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-ods/" name="DOTM Do ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/dotm-to-tsv/" name="DOTM Do TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}