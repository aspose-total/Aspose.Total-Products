---
title: Преобразование формата JSON в MOBI через C++
description: C++ API t0 Анализировать JSON в MOBI без использования Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: WORD FLATOPC DOT RTF DOCM WORDML CHM OTT PS DOTX EPUB ODT PCL DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование формата JSON в MOBI через C++" h2="Преобразование JSON в MOBI в приложениях C++ без использования Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for C++](https://products.aspose.com/total/cpp/), вы можете преобразовать JSON в MOBI в своих приложениях C++ в два простых шага. Во-первых, с помощью [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) вы можете экспортировать JSON в PDF. После этого, используя [Aspose.Words for C++](https://products.aspose.com/words/cppp/), вы сможете конвертировать PDF в MOBI. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в MOBI на C++" %}}
1. Создайте новый объект [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) и прочитайте действительные данные JSON из файла.
2. Сохраните JSON как PDF, используя метод [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997).
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Сохраните документ в формате MOBI, используя метод [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите через консоль диспетчера пакетов Visual Studio с помощью Install-Package Aspose.Total.Cpp.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в MOBI в C++" %}}
При синтаксическом анализе JSON в MOBI вы также можете установить размер строк и столбцов, загрузив JSON с классом [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Если вам нужно установить одинаковую высоту строки для всех строк на листе, вы можете сделать это с помощью [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) метод коллекции [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Точно так же, чтобы установить одинаковую ширину столбца для всех столбцов на листе, используйте метод [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) коллекции ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование формата JSON в MOBI с водяным знаком на C++" %}}
Используя API, вы также можете преобразовать JSON в MOBI с водяным знаком. Чтобы добавить водяной знак в документ MOBI, вы можете сначала преобразовать JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), установите различные свойства для текстового водяного знака,
вызовите метод SetText и передайте текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в MOBI.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}