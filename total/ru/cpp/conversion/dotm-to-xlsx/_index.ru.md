---
title: Преобразование DOTM в XLSX на C++
description: C++ API для преобразования DOTM в XLSX без использования Microsoft Word или Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLSX
otherformats: XLSB TSV ODS XLTX EXCEL FODS SXC XLT DIF XLSM CSV XLAM XLS XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для преобразования DOTM в XLSX" h2="Экспорт DOTM в XLSX через C++ без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете легко включить функцию преобразования DOTM в XLSX в свои приложения C++. Используя многофункциональный, мощный и простой в использовании API для работы с документами и преобразования [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать DOTM в HTML. После этого, используя [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), вы можете конвертировать HTML в XLSX. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования DOTM в XLSX" %}}
1. Откройте файл DOTM, используя ссылку на класс [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument).
2. Преобразуйте DOTM в HTML с помощью функции-члена [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string_saveformat).
3. Загрузите HTML-документ, используя ссылку на класс [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
4. Сохраните документ в формате XLSX, используя функцию-член [Сохранить](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Доступ к свойствам документа DOTM через C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) также позволяет вам получить доступ к свойствам документа файла DOTM и позволяет принять обоснованное решение до процесса преобразования. Для доступа к свойствам документа вы можете использовать [BuiltInDotmumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotmument_properties) для получения встроенных свойств и [CustomDotmumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotmument_properties), чтобы получить настраиваемые свойства. В следующем примере кода показано, как перечислить все встроенные и настраиваемые свойства в документе.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotmument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Сохранить файл XLSX для потоковой передачи через C++" %}}
После преобразования DOTM в XLSX [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) позволяет сохранить документ для потоковой передачи. Чтобы сохранить файлы в потоке, создайте объект MemoryStream или FileStream и сохраните файл в этом объекте потока, вызвав [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Сохранить](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) объекта. Укажите желаемый формат файла с помощью перечисления [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) при вызове [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xlsb/" name="DOTM К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-tsv/" name="DOTM К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-ods/" name="DOTM К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xltx/" name="DOTM К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-excel/" name="DOTM К EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-fods/" name="DOTM К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-sxc/" name="DOTM К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xlt/" name="DOTM К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-dif/" name="DOTM К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xlsm/" name="DOTM К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xlsx/" name="DOTM К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xlam/" name="DOTM К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xls/" name="DOTM К XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-xltm/" name="DOTM К XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}