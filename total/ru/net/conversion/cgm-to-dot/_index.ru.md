---
title: C# API для экспорта CGM в DOT
description: Преобразование CGM в DOT без использования Microsoft Word
url_ignore: /ru/net/conversion/cgm-to-dot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOT
otherformats: PCL FLATOPC OTT WORDML ODT DOT RTF MARKDOWN XAMLFLOW DOTX PS MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг CGM в DOT через .NET" h2=".NET API для экспорта CGM в DOT в Windows, macOS и Linux без использования Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) — это мощный API для добавления функций обработки и преобразования документов в ваше приложение .NET. Используя расширенный API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файлов CGM в DOC. После этого, используя мощный API обработки документов [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать DOC в DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования CGM в DOT" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте CGM в Doc, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл Doc с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document) Aspose.Words.
4. Сохраните документ в формате DOT с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Dot как SaveFormat.
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
Перед преобразованием CGM в DOT, если вы хотите расшифровать свой документ, вы можете сделать это с помощью API. Чтобы расшифровать файл PDF, сначала необходимо создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть CGM, используя пароль владельца. После этого необходимо вызвать метод [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) объекта Document. Наконец, сохраните обновленный файл, используя метод Save объекта Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать DOT-файл только для чтения через .NET" %}}
Чтобы защитить ваш DOT от редактирования и предотвратить редактирование важной и конфиденциальной информации в вашем документе другими людьми, вы также можете установить защиту документа с помощью API. Вы можете ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это можно сделать с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Это позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в DOT: примеры использования" %}}
Преобразование файлов CGM в формат DOT позволяет раскрыть полную функциональность вашей возможностей визуализации графов и настройки layouts. Это преобразование позволяет:

**Использования:**

*   **Визуализация графов**: Преобразовать файлы CGM в формат DOT для создания диаграмм, схем потоков и процессных карт, которые идеально подходят для представления сложных отношений между данными.
*   **Оптимизация layouts**: Использовать формат DOT для настройки узлов и дуг в ваших графах, обеспечивая максимальную читаемость и эффективность.
*   **Маркировка бизнес-процессов**: Преобразовать файлы CGM в детальные схемы бизнес-процессов, подчеркивая рабочие процессы, задачи и точки принятия решений.
*   **Технические диаграммы**: Создавать технические схемы, такие как диаграммы классов UML, диаграммы потока данных и ER, с использованием формата DOT.
*   **Иерархия и структура графов**: Преобразовать файлы CGM для установления ясных иерархией и структуры в ваших графах, упрощая навигацию и понимание.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}