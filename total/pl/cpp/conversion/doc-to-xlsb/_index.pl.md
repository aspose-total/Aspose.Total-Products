---
title: Konwertuj DOC na XLSB w C++
description: C++ API do konwersji DOC na XLSB bez używania Microsoft Word lub Microsoft Excel
url: /pl/cpp/conversion/doc-to-xlsb/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLSB
otherformats: XLTM XLAM XLSM FODS CSV EXCEL XLS SXC XLTX XLT ODS TSV DIF XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do konwersji DOC na XLSB" h2="Eksportuj DOC do XLSB za pomocą C++ bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz łatwo włączyć funkcję konwersji DOC do XLSB w swoich aplikacjach C++. Korzystając z bogatego w funkcje, wydajnego i łatwego w użyciu interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz eksportować DOC do HTML. Następnie, używając [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), możesz przekonwertować HTML na XLSB. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji DOC na XLSB" %}}
1. Otwórz plik DOC, korzystając z odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Konwertuj DOC na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. Załaduj dokument HTML, używając odwołania do klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Zapisz dokument w formacie XLSB za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj dostęp do właściwości dokumentu DOC za pomocą C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) umożliwia również dostęp do właściwości dokumentu pliku DOC i pozwala podjąć świadomą decyzję przed procesem konwersji. Aby uzyskać dostęp do właściwości dokumentu, możesz użyć [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties), aby uzyskać wbudowane właściwości i [CustomDocumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties), aby uzyskać właściwości niestandardowe. Poniższy przykład kodu pokazuje, jak wyliczyć wszystkie wbudowane i niestandardowe właściwości w dokumencie.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Zapisz plik XLSB w strumieniu za pomocą C++" %}}
Po przekonwertowaniu DOC na XLSB [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Aby zapisać pliki w strumieniu, utwórz obiekt MemoryStream lub FileStream i zapisz plik w tym obiekcie strumienia, wywołując [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metoda obiektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Określ żądany format pliku, używając wyliczenia [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) podczas wywoływania [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xltm/" name="DOC Do XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xlam/" name="DOC Do XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xlsm/" name="DOC Do XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-fods/" name="DOC Do FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xlsb/" name="DOC Do XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-excel/" name="DOC Do EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xls/" name="DOC Do XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-sxc/" name="DOC Do SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xltx/" name="DOC Do XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xlt/" name="DOC Do XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-ods/" name="DOC Do ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-tsv/" name="DOC Do TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-dif/" name="DOC Do DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/doc-to-xlsx/" name="DOC Do XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}