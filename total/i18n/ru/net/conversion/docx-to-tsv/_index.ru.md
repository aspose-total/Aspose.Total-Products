---
title: .NET API для преобразования DOCX в TSV
description: C# API для преобразования DOCX в TSV без использования Microsoft Excel или Adobe Reader
url: /ru/net/conversion/docx-to-tsv/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: TSV
otherformats: XLTX FODS XLAM XLSM XLSX XLTM SXC DIF XLS TSV ODS XLT XLSB EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для преобразования DOCX в TSV" h2="Экспорт DOCX в TSV с помощью C# без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете включить функцию преобразования DOCX в TSV в любое приложение .NET, C#, ASP.NET и VB.NET в два простых шага. Во-первых, с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) вы можете экспортировать DOCX в HTML. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API для программирования электронных таблиц, вы можете конвертировать HTML в TSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования DOCX в TSV" %}}
1. Откройте файл DOCX, используя класс [Docxument](https://apireference.aspose.com/words/net/aspose.words/docxument).
2. Преобразуйте DOCX в HTML, используя метод [Сохранить](https://apireference.aspose.com/words/net/aspose.words.docxument/save/methods/4).
3. Загрузите HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате TSV с помощью метода [Сохранить] (https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите «TSV» в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Загрузить документ DOCX из потока через С#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) также позволяет загружать документ DOCX через поток. Чтобы открыть документ из потока, просто передайте объект потока, содержащий документ, в конструктор [Docxument](https://apireference.aspose.com/words/net/aspose.words/docxument). В следующем примере кода показано, как открыть документ из потока:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Добавить пользовательские свойства в файл TSV через С#" %}}
При преобразовании DOCX в TSV [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) позволяет добавлять пользовательские свойства в документы TSV. Чтобы добавить пользовательское свойство, вы можете использовать метод [Добавить](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocxumentpropertycollection/methods/add/index) для [CustomDocxumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocxumentpropertycollection). Метод Add добавляет свойство в файл Excel и возвращает ссылку на новое свойство документа в виде [Aspose.Cells.Properties.DocxumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties). /docxumentproperty) объект. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-dif/" name="DOCX в DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlsb/" name="DOCX в XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-tsv/" name="DOCX в TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-fods/" name="DOCX в FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlt/" name="DOCX в XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-excel/" name="DOCX в EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlsx/" name="DOCX в XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-ods/" name="DOCX в ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-sxc/" name="DOCX в SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlam/" name="DOCX в XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xltm/" name="DOCX в XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlsm/" name="DOCX в XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xls/" name="DOCX в XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xltx/" name="DOCX в XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}