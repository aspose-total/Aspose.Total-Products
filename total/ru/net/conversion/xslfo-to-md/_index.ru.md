---
title: Преобразование XSLFO в MD через C# API
description: C# API для преобразования файла XSLFO в MD без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/xslfo-to-md/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: MD
otherformats: FODS TSV XLSB XLAM MD XLT SXC XLSM DIF XLTX XLTM TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для рендеринга XSLFO в MD" h2="Экспорт файла XSLFO в MD с помощью C# без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко конвертировать файл XSLFO в MD в любых приложениях .NET, C#, ASP.NET и VB.NET. Во-первых, используя [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать XSLFO в XLSX. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API программирования электронных таблиц, вы можете конвертировать XLSX в MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования XSLFO в MD" %}}
1. Откройте файл XSLFO, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте XSLFO в XLSX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате MD с помощью метода [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите `Md` в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного XSLFO в MD через C#" %}}
Если ваш документ XSLFO защищен паролем, вы не сможете преобразовать его в MD без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла XSLFO в MD с водяным знаком через C#" %}}
При преобразовании файла XSLFO в MD вы также можете добавить водяной знак в выходной формат файла MD. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный документ XLSX, выбрать Worksheet через его индекс, создать форму и использовать ее функцию AddTextEffect. После этого вы можете сохранить документ XLSX в формате MD с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}