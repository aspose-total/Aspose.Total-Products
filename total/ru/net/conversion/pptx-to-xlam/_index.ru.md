---
title: Преобразование PPTX в XLAM через C#
description: Преобразование PPTX в XLAM на C# без использования Microsoft Excel или Powerpoint
url_ignore: /ru/net/conversion/pptx-to-xlam/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: XLAM
otherformats: XLSB XLAM SXC TSV MHTML EXCEL XLTM XLS XLSX XLSM FODS XLT MARKDOWN ODS DIF XLTX DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PPTX в XLAM через C#" h2=".NET API для преобразования PPTX в XLAM без использования Microsoft<sup>&reg;</sup> Excel или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете преобразовать файл PPTX в XLAM в любом приложении .NET, C#, ASP.NET и VB.NET в два этапа. простые шаги. Во-первых, с помощью [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете экспортировать PPTX в HTML. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API для программирования электронных таблиц, вы можете конвертировать HTML в XLAM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать PPTX в XLAM через C#" %}}
1. Откройте файл PPTX, используя класс [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
2. Экспортируйте PPTX как HTML, используя метод [Сохранить](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5).
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате XLAM, используя метод [Сохранить](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного PPTX в XLAM через C#" %}}
При преобразовании файла PPTX в XLAM, если ваш входной документ PPTX защищен паролем, вы не можете преобразовать его в XLAM без расшифровки документа. Когда ваш документ защищен паролем, это означает, что он налагает определенные ограничения на представление. Для снятия ограничений необходимо ввести пароль. Презентация, защищенная паролем, считается заблокированной презентацией. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PPTX в XLAM с водяным знаком через C#" %}}
При преобразовании файла PPTX в XLAM вы также можете добавить водяной знак в формат выходного файла XLAM. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный HTML-документ, выбрать Worksheet через его индекс, создать Shape и использовать его функцию AddTextEffect. После этого вы можете сохранить свой HTML-документ в формате XLAM с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-fods/" name="PPTX в FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xltm/" name="PPTX в XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xlt/" name="PPTX в XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xlam/" name="PPTX в XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-markdown/" name="PPTX в MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-excel/" name="PPTX в EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-mhtml/" name="PPTX в MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xlsb/" name="PPTX в XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-ods/" name="PPTX в ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-sxc/" name="PPTX в SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xls/" name="PPTX в XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xltx/" name="PPTX в XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xlsx/" name="PPTX в XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-tsv/" name="PPTX в TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-dif/" name="PPTX в DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-xlsm/" name="PPTX в XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-doc/" name="PPTX в DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-docx/" name="PPTX в DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-docm/" name="PPTX в DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-dot/" name="PPTX в DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-dotm/" name="PPTX в DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-dotx/" name="PPTX в DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-odt/" name="PPTX в ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-ott/" name="PPTX в OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-rtf/" name="PPTX в RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-word/" name="PPTX в WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-wordml/" name="PPTX в WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-text/" name="PPTX в TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pptx-to-flatopx/" name="PPTX в FLAвPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}