---
title: C# API для экспорта CGM в RTF
description: Преобразование CGM в RTF без использования Microsoft Word
url_ignore: /ru/net/conversion/cgm-to-rtf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: RTF
otherformats: MHTML WORDML OTT PS XAMLFLOW DOT ODT PCL RTF DOTX FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг CGM в RTF через .NET" h2=".NET API для экспорта CGM в RTF в Windows, macOS и Linux без использования Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) — это мощный API для добавления функций обработки и преобразования документов в ваше приложение .NET. Используя расширенный API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файлов CGM в DOC. После этого, используя мощный API обработки документов [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать DOC в RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования CGM в RTF" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте CGM в Doc, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл Doc с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document) Aspose.Words.
4. Сохраните документ в формате RTF с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Rtf как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Расшифровать файл CGM с помощью пароля владельца через .NET" %}}
Перед преобразованием CGM в RTF, если вы хотите расшифровать свой документ, вы можете сделать это с помощью API. Чтобы расшифровать файл PDF, сначала необходимо создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть CGM, используя пароль владельца. После этого необходимо вызвать метод [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) объекта Document. Наконец, сохраните обновленный файл, используя метод Save объекта Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать RTF-файл только для чтения через .NET" %}}
Чтобы защитить ваш RTF от редактирования и предотвратить редактирование важной и конфиденциальной информации в вашем документе другими людьми, вы также можете установить защиту документа с помощью API. Вы можете ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это можно сделать с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Это позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в RTF: примеры использования" %}}
CGM (Computer Graphics Metafile) файлы используются для хранения информации о векторных графических изображениях, что делает их идеальным выбором для создания статических графических изображений и иллюстраций. Однако при работе с динамической информацией, такие таблицы как Excel становятся необходимостью для визуализации данных и анализа.

Приведение CGM файлов в соответствие RTF форматам позволяет раскрыть полные возможности текстовых возможностей. Это позволяет:

**Использованиям делается следующее:**

*   **Создание документов**: Приведение CGM файлов к созданию профессионально оформленных документов, отчетов и презентаций.
*   **Редактирование и форматирование текста**: Использование RTF для точного контроля над стилями шрифтов, размерами, цветами и расположением текста.
*   **Шаблоны писем и писем**: Приведение CGM файлов к созданию настраиваемых шаблонов писем, писем и других деловых переписок.
*   **Десктопное издательство**: Использование RTF для создания высококачественных документов, буклетов и других материалов для внутреннего или внешнего распределения.
*   **Техническая работа**: Приведение CGM файлов к созданию технических документов, руководств пользователя и инструкций с точным контролем над форматированием и расположением.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}