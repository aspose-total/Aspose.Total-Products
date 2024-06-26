---
title: Преобразовать формат DOCX в JSON на C++
description: Экспорт DOCX в JSON на C++ без использования Microsoft Excel или Word

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование DOCX в формат JSON через C++" h2="Экспорт DOCX в JSON через C++ без использования Microsoft<sup>&reg;</sup> Word или Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for C++](https://products.aspose.com/total/cpp/), вы можете конвертировать DOCX в формат JSON в своих приложениях C++. Во-первых, с помощью [Aspose.Words for C++](https://products.aspose.com/words/cpp/) вы можете экспортировать DOCX в HTML. После этого, используя [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), вы можете конвертировать HTML в формат JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование DOCX в формат JSON через C++" %}}
1. Откройте файл DOCX, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
2. Преобразуйте DOCX в HTML с помощью функции-члена [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
3. Загрузите HTML-документ, используя ссылку на класс [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
4. Сохраните документ в формате JSON с помощью функции-члена [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите через консоль диспетчера пакетов Visual Studio с помощью Install-Package Aspose.Total.Cpp.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Конвертировать защищенный DOCX в формат JSON через C++" %}}
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной документ DOCX защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. Для этого используйте специальную перегрузку конструктора, которая принимает объект LoadOptions. Этот объект содержит свойство Password, которое определяет строку пароля.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}