---
title: Преобразование DOC в XLSM на C++
description: C++ API для преобразования DOC в XLSM без использования Microsoft Word или Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLSM
otherformats: XLAM XLTM FODS XLTX XLS ODS XLT TSV XLSX SXC DIF XLSB EXCEL CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для преобразования DOC в XLSM" h2="Экспорт DOC в XLSM через C++ без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете легко включить функцию преобразования DOC в XLSM в свои приложения C++. Используя многофункциональный, мощный и простой в использовании API для работы с документами и преобразования [Aspose.Words for C++](https://products.aspose.com/words/cpp/), вы можете экспортировать DOC в HTML. После этого, используя [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), вы можете конвертировать HTML в XLSM. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования DOC в XLSM" %}}
1. Откройте файл DOC, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
2. Преобразуйте DOC в HTML с помощью функции-члена [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
3. Загрузите HTML-документ, используя ссылку на класс [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
4. Сохраните документ в формате XLSM, используя функцию-член [Сохранить](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Доступ к свойствам документа DOC через C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) также позволяет вам получить доступ к свойствам документа файла DOC и позволяет принять обоснованное решение до процесса преобразования. Для доступа к свойствам документа вы можете использовать [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) для получения встроенных свойств и [CustomDocumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties), чтобы получить настраиваемые свойства. В следующем примере кода показано, как перечислить все встроенные и настраиваемые свойства в документе.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Сохранить файл XLSM для потоковой передачи через C++" %}}
После преобразования DOC в XLSM [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) позволяет сохранить документ для потоковой передачи. Чтобы сохранить файлы в потоке, создайте объект MemoryStream или FileStream и сохраните файл в этом объекте потока, вызвав [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Сохранить](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) объекта. Укажите желаемый формат файла с помощью перечисления [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) при вызове [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xlam/" name="DOC К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xltm/" name="DOC К XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-fods/" name="DOC К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xltx/" name="DOC К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xls/" name="DOC К XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-ods/" name="DOC К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xlt/" name="DOC К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-tsv/" name="DOC К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xlsx/" name="DOC К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-sxc/" name="DOC К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-dif/" name="DOC К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xlsb/" name="DOC К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-excel/" name="DOC К EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/doc-to-xlsm/" name="DOC К XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}