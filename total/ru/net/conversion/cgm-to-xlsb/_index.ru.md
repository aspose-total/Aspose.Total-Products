---
title: Преобразование CGM в XLSB через C# API
description: C# API для преобразования файла CGM в XLSB без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/cgm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSB
otherformats: XLSB TSV XLTX ODS XLSM XLT XLTM EXCEL SXC TXT FODS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для рендеринга CGM в XLSB" h2="Экспорт файла CGM в XLSB с помощью C# без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко конвертировать файл CGM в XLSB в любых приложениях .NET, C#, ASP.NET и VB.NET. Во-первых, используя [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать CGM в XLSX. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API программирования электронных таблиц, вы можете конвертировать XLSX в XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования CGM в XLSB" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте CGM в XLSX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате XLSB с помощью метода [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите `Xlsb` в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного CGM в XLSB через C#" %}}
Если ваш документ CGM защищен паролем, вы не сможете преобразовать его в XLSB без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла CGM в XLSB с водяным знаком через C#" %}}
При преобразовании файла CGM в XLSB вы также можете добавить водяной знак в выходной формат файла XLSB. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный документ XLSX, выбрать Worksheet через его индекс, создать форму и использовать ее функцию AddTextEffect. После этого вы можете сохранить документ XLSX в формате XLSB с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в XLSB: примеры использования" %}}
Файлы CGM (Computer Graphics Metafile) используются для хранения информации о векторных графических данных, что делает их идеальным выбором для создания статических графиков и иллюстраций. Однако при работе с динамическими данными, такие как Excel, становятся необходимыми для визуализации данных и анализа.

Преобразование файлов CGM в форматы Excel позволяет раскрыть полные возможности вашей способности к визуализации и анализу данных. Это делает возможным следующее:

**Применения:**

*   **Переход на оптимизацию статических графиков, логотипов и иконок с точным управлением цветами, формами и размерами.**
*   **Использование Excel для редактирования векторных график, слияния изображений и добавления текста или эффектов для улучшения иллюстраций и визуального контента.**
*   **Переход на создание интерактивных буклетов, организацию содержимого и легкий подбор layout.**
*   **Использование Excel для создания привлекательных инфографиков, организации данных и визуализации сложной информации в четкой и краткой форме.**
*   **Переход на генерацию интерактивных отчетов, отслеживание ключевых показателей (КПИ) и создание высококачественных визуализаций для бизнес-洞察ств.**
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}