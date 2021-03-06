---
title: Преобразование PPS в FODS через C#
description: Преобразование PPS в FODS на C# без использования Microsoft Excel или Powerpoint
url_ignore: /ru/net/conversion/pps-to-fods/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: FODS
otherformats: TSV DIF XLAM XLS SXC ODS XLTM XLSM FODS XLTX EXCEL MARKDOWN MHTML XLSB XLT XLSX DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PPS в FODS через C#" h2=".NET API для преобразования PPS в FODS без использования Microsoft<sup>&reg;</sup> Excel или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете преобразовать файл PPS в FODS в любом приложении .NET, C#, ASP.NET и VB.NET в два этапа. простые шаги. Во-первых, с помощью [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете экспортировать PPS в HTML. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API для программирования электронных таблиц, вы можете конвертировать HTML в FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать PPS в FODS через C#" %}}
1. Откройте файл PPS, используя класс [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
2. Экспортируйте PPS как HTML, используя метод [Сохранить](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5).
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате FODS, используя метод [Сохранить](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного PPS в FODS через C#" %}}
При преобразовании файла PPS в FODS, если ваш входной документ PPS защищен паролем, вы не можете преобразовать его в FODS без расшифровки документа. Когда ваш документ защищен паролем, это означает, что он налагает определенные ограничения на представление. Для снятия ограничений необходимо ввести пароль. Презентация, защищенная паролем, считается заблокированной презентацией. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PPS в FODS с водяным знаком через C#" %}}
При преобразовании файла PPS в FODS вы также можете добавить водяной знак в формат выходного файла FODS. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный HTML-документ, выбрать Worksheet через его индекс, создать Shape и использовать его функцию AddTextEffect. После этого вы можете сохранить свой HTML-документ в формате FODS с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-fods/" name="PPS в FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xltm/" name="PPS в XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xlt/" name="PPS в XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xlam/" name="PPS в XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-markdown/" name="PPS в MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-excel/" name="PPS в EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-mhtml/" name="PPS в MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xlsb/" name="PPS в XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-ods/" name="PPS в ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-sxc/" name="PPS в SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xls/" name="PPS в XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xltx/" name="PPS в XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xlsx/" name="PPS в XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-tsv/" name="PPS в TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dif/" name="PPS в DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-xlsm/" name="PPS в XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-doc/" name="PPS в DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-docx/" name="PPS в DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-docm/" name="PPS в DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dot/" name="PPS в DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dotm/" name="PPS в DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dotx/" name="PPS в DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-odt/" name="PPS в ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-ott/" name="PPS в OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-rtf/" name="PPS в RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-word/" name="PPS в WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-wordml/" name="PPS в WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-text/" name="PPS в TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-flatopx/" name="PPS в FLAвPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}