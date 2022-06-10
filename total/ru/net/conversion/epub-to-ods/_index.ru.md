---
title: Преобразование EPUB в ODS через C# API
description: C# API для преобразования файла EPUB в ODS без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/epub-to-ods/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODS
otherformats: DIF XLTX FODS SXC XLAM XLSB TXT MD XLSM XLTM ODS XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для рендеринга EPUB в ODS" h2="Экспорт файла EPUB в ODS с помощью C# без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете легко конвертировать файл EPUB в ODS в любых приложениях .NET, C#, ASP.NET и VB.NET. Во-первых, используя [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать EPUB в XLSX. После этого, используя [Aspose.Cells для .NET](https://products.aspose.com/cells/net/) API программирования электронных таблиц, вы можете конвертировать XLSX в ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования EPUB в ODS" %}}
1. Откройте файл EPUB, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте EPUB в XLSX, используя метод [Сохранить](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате ODS с помощью метода [Сохранить](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите `Ods` в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного EPUB в ODS через C#" %}}
Если ваш документ EPUB защищен паролем, вы не сможете преобразовать его в ODS без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла EPUB в ODS с водяным знаком через C#" %}}
При преобразовании файла EPUB в ODS вы также можете добавить водяной знак в выходной формат файла ODS. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный документ XLSX, выбрать Worksheet через его индекс, создать форму и использовать ее функцию AddTextEffect. После этого вы можете сохранить документ XLSX в формате ODS с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-sxc/" name="EPUB в SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xltx/" name="EPUB в XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-md/" name="EPUB в MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-tsv/" name="EPUB в TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-txt/" name="EPUB в TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-ods/" name="EPUB в ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xlt/" name="EPUB в XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xlsm/" name="EPUB в XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xlam/" name="EPUB в XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xltm/" name="EPUB в XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-dif/" name="EPUB в DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xlsb/" name="EPUB в XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}