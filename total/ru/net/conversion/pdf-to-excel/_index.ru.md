---
title: Преобразование PDF в Excel через C# API
description: C# API для преобразования файла PDF в Excel без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/pdf-to-excel/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: EXCEL
otherformats: MD XLTX DIF ODS SXC TXT XLTM XLSM FODS TSV XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для рендеринга PDF в Excel" h2="Экспорт файла PDF в Excel с помощью C# без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2 class="heading-border">Зачем конвертировать PDF в форматы Excel?</h2>

Конвертация PDF в форматы Excel с использованием .NET API имеет несколько важных преимуществ. Во-первых, Excel - это мощное средство для анализа и обработки данных, и конвертация PDF в Excel позволяет легко извлекать структурированные данные из PDF-документов и использовать их для расчетов, визуализации и создания отчетов. Во-вторых, это обеспечивает совместимость данных между различными приложениями и системами, что делает их более доступными и удобными для обработки и анализа. Кроме того, .NET API упрощает процесс конвертации, автоматизируя его и позволяя интегрировать эту функциональность в существующие .NET-приложения, что экономит время и повышает эффективность работы с данными.

<h2 class="heading-border">Как Aspose.Total может помочь в преобразовании PDF в Excel?</h2>

С [Aspose.Total for .NET](https://products.aspose.com/total/net/), легко выполнять конвертацию файлов PDF в Excel в приложениях .NET, таких как C#, ASP.NET и VB.NET. В первую очередь, с помощью Aspose.PDF for .NET, вы можете произвести экспорт PDF в формат XLSX. Затем, с применением Aspose.Cells for .NET - API для работы с электронными таблицами, вы можете произвести конвертацию XLSX в формат Excel. Это упрощает процесс конвертации и делает его доступным для интеграции в приложения на .NET, сэкономив время и повысив эффективность работы с данными.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования PDF в Excel" %}}
1. Откройте файл PDF, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте PDF в XLSX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате Excel с помощью метода [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите `Excel` в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного PDF в Excel через C#" %}}
Если ваш документ PDF защищен паролем, вы не сможете преобразовать его в Excel без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла PDF в Excel с водяным знаком через C#" %}}
При преобразовании файла PDF в Excel вы также можете добавить водяной знак в выходной формат файла Excel. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный документ XLSX, выбрать Worksheet через его индекс, создать форму и использовать ее функцию AddTextEffect. После этого вы можете сохранить документ XLSX в формате Excel с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}