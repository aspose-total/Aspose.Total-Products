---
title: Преобразование WORD в формат JSON через .NET
description: Преобразование WORD в JSON на C# без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/word-to-json/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: JSON
otherformats: XLSX XLSM XLS XLT CSV TSV EXCEL XLSB SXC FODS DIF ODS XLTM XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование WORD в формат JSON через С#" h2="Преобразование WORD в JSON с помощью C# без использования Microsoft<sup>&reg;</sup> Word или Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете конвертировать WORD в формат JSON в любом приложении .NET, C#, ASP.NET и VB.NET в два этапа. простые шаги. Во-первых, с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) вы можете экспортировать WORD в HTML. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API для программирования электронных таблиц, вы можете конвертировать HTML в JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование WORD в формат JSON через С#" %}}
1. Откройте файл WORD, используя класс [Document](https://reference.aspose.com/words/net/aspose.words/document).
2. Преобразуйте WORD в HTML, используя метод [Сохранить](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4).
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате JSON, используя метод [Сохранить](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного документа WORD в формат JSON с помощью C#" %}}
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной документ WORD защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions. В следующем примере кода показано, как попытаться открыть зашифрованный документ с помощью пароля:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование WORD в JSON в диапазоне через C#" %}}
Пока вы конвертируете WORD в JSON, вы также можете установить диапазон выходного формата JSON. Чтобы установить диапазон, вы можете открыть преобразованный HTML с помощью класса Workbook, получить CellsCollection рабочего листа, содержащего данные, создать диапазон из CellsCollection, указав индексы строк и столбцов, и вызвать метод ExportRangeToJson со ссылками на объекты Range и ExportRangeToJsonOptions. Наконец, вы можете сохранить данные JSON в файл с помощью метода File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-csv/" name="WORD в CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlam/" name="WORD в XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-sxc/" name="WORD в SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-tsv/" name="WORD в TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlt/" name="WORD в XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-excel/" name="WORD в EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-dif/" name="WORD в DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlsm/" name="WORD в XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xltm/" name="WORD в XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlsx/" name="WORD в XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlsb/" name="WORD в XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-fods/" name="WORD в FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-ods/" name="WORD в ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xltx/" name="WORD в XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}