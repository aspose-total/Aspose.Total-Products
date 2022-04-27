---
title: .NET API для преобразования DOTX в ODS
description: C# API для преобразования DOTX в ODS без использования Microsoft Excel или Adobe Reader
url: /ru/net/conversion/dotx-to-ods/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: ODS
otherformats: ODS DIF TSV XLS XLT XLTX XLSX EXCEL XLSB XLTM XLSM SXC XLAM FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для преобразования DOTX в ODS" h2="Экспорт DOTX в ODS с помощью C# без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете включить функцию преобразования DOTX в ODS в любое приложение .NET, C#, ASP.NET и VB.NET в два простых шага. Во-первых, с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) вы можете экспортировать DOTX в HTML. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API для программирования электронных таблиц, вы можете конвертировать HTML в ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования DOTX в ODS" %}}
1. Откройте файл DOTX, используя класс [Dotxument](https://apireference.aspose.com/words/net/aspose.words/dotxument).
2. Преобразуйте DOTX в HTML, используя метод [Сохранить](https://apireference.aspose.com/words/net/aspose.words.dotxument/save/methods/4).
3. Загрузите HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате ODS с помощью метода [Сохранить](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите «ODS» в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Загрузить документ DOTX из потока через С#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) также позволяет загружать документ DOTX через поток. Чтобы открыть документ из потока, просто передайте объект потока, содержащий документ, в конструктор [Dotxument](https://apireference.aspose.com/words/net/aspose.words/dotxument). В следующем примере кода показано, как открыть документ из потока:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Добавить пользовательские свойства в файл ODS через С#" %}}
При преобразовании DOTX в ODS [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) позволяет добавлять пользовательские свойства в документы ODS. Чтобы добавить пользовательское свойство, вы можете использовать метод [Добавить](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotxumentpropertycollection/methods/add/index) для [CustomDotxumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotxumentpropertycollection). Метод Add добавляет свойство в файл Excel и возвращает ссылку на новое свойство документа в виде [Aspose.Cells.Properties.DotxumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties). /dotxumentproperty) объект. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-dif/" name="DOTX в DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlsb/" name="DOTX в XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-tsv/" name="DOTX в TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-fods/" name="DOTX в FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlt/" name="DOTX в XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-excel/" name="DOTX в EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlsx/" name="DOTX в XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-ods/" name="DOTX в ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-sxc/" name="DOTX в SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlam/" name="DOTX в XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xltm/" name="DOTX в XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlsm/" name="DOTX в XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xls/" name="DOTX в XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xltx/" name="DOTX в XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}