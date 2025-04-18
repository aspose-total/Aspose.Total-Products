---
title: Преобразование CGM в TXT через C# API
description: C# API для преобразования файла CGM в TXT без использования Microsoft Excel или Adobe Reader
url_ignore: /ru/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API для рендеринга CGM в TXT" h2="Экспорт файла CGM в TXT с помощью C# без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко конвертировать файл CGM в TXT в любых приложениях .NET, C#, ASP.NET и VB.NET. Во-первых, используя [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете экспортировать CGM в XLSX. После этого, используя [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API программирования электронных таблиц, вы можете конвертировать XLSX в TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования CGM в TXT" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте CGM в XLSX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
4. Сохраните документ в формате TXT с помощью метода [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) и установите `Txt` в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного CGM в TXT через C#" %}}
Если ваш документ CGM защищен паролем, вы не сможете преобразовать его в TXT без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр класса [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование файла CGM в TXT с водяным знаком через C#" %}}
При преобразовании файла CGM в TXT вы также можете добавить водяной знак в выходной формат файла TXT. Чтобы добавить водяной знак, вы можете создать новый объект Workbook и открыть преобразованный документ XLSX, выбрать Worksheet через его индекс, создать форму и использовать ее функцию AddTextEffect. После этого вы можете сохранить документ XLSX в формате TXT с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в TXT: примеры использования" %}}
Файлы CGM (Computer Graphics Metafile) используются для хранения информации о векторных графических данных, что делает их идеальным выбором для создания статических изображений и иллюстраций. Однако при работе с динамическими данными текстовые редакторы, такие как Notepad, становятся необходимостью для базовых операций по редактированию текста и документации.

Преобразование файлов CGM в форматы plain text позволяет раскрыть полные возможности вашей способности к редактированию текста. Это преобразование позволяет:

**Использованиям случаев:**

*   **Документирование данных**: Преобразовать файлы CGM в читаемый для человека текст, что упрощает понимание и передачу информации о графических данных.
*   **Редактирование текста**: Использовать Notepad для редактирования и манипуляции с plain text, извлеченным из файлов CGM, для выполнения базовых задач по редактированию текста.
*   **Создание ASCII-искусства**: Преобразовать файлы CGM в ASCII-искусство, создавая простые, текстовые представления изображений для целей художественного или декоративного назначения.
*   **Импорт данных в другие инструменты**: Использовать преобразование в plain text для импорта графических данных в другие текстовые редакторы или программы обработки текста, расширяя возможности по манипуляции текстом.
*   **Базовое отчетирование и debugging**: Преобразовать файлы CGM в базовые отчеты и логи, помогающие в выявлении ошибок и проблем во время процесса разработки.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}