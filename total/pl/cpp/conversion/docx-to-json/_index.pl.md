---
title: Konwertuj DOCX na format JSON w C++
description: Eksportuj DOCX do JSON w C++ bez użycia Microsoft Excel lub Word

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj DOCX na format JSON za pomocą C++" h2="Eksportuj DOCX do JSON przez C++ bez używania Microsoft<sup>&reg;</sup> Word lub Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for C++](https://products.aspose.com/total/cpp/) możesz przekonwertować DOCX na format JSON w swoich aplikacjach C++. Po pierwsze, używając [Aspose.Words for C++](https://products.aspose.com/words/cpp/), możesz wyeksportować DOCX do HTML. Następnie, używając [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), możesz przekonwertować HTML na format JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj DOCX na format JSON za pomocą C++" %}}
1. Otwórz plik DOCX, korzystając z odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Konwertuj DOCX na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. Załaduj dokument HTML, używając odwołania do klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Zapisz dokument w formacie JSON za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony DOCX na format JSON za pomocą C++" %}}
Korzystając z interfejsu API, możesz również otworzyć dokument chroniony hasłem. Jeśli wejściowy dokument DOCX jest chroniony hasłem, nie można go przekonwertować na format JSON bez użycia hasła. Aby to zrobić, użyj specjalnego przeciążenia konstruktora, które akceptuje obiekt LoadOptions. Ten obiekt zawiera właściwość Password, która określa ciąg hasła.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}