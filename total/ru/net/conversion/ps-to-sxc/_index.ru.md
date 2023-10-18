---
title: Преобразование PS в SXC через C# API
description: C# API для преобразования файла PS в SXC без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/ps-to-sxc/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SXC
otherformats: MD FODS XLAM DIF ODS XLSM XLSB TSV EXCEL SXC TXT XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для рендеринга PS в SXC" h2="Экспорт файла PS в SXC с помощью C# без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко конвертировать файл PS в SXC в любых приложениях .NET, C#, ASP.NET и VB.NET. Во-первых, используя [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать PS в XLSX. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API программирования электронных таблиц, вы можете конвертировать XLSX в SXC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования PS в SXC" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте PS в XLSX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате SXC с помощью метода [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите `Sxc` в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного PS в SXC через C#" %}}
Если ваш документ PS защищен паролем, вы не сможете преобразовать его в SXC без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла PS в SXC с водяным знаком через C#" %}}
При преобразовании файла PS в SXC вы также можете добавить водяной знак в выходной формат файла SXC. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный документ XLSX, выбрать Worksheet через его индекс, создать форму и использовать ее функцию AddTextEffect. После этого вы можете сохранить документ XLSX в формате SXC с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}