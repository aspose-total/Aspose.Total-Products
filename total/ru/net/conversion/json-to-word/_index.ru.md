---
title: Преобразование формата JSON в WORD через .NET
description: Разобрать JSON в WORD на C# без использования Microsoft Word
url_ignore: /ru/net/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORD
otherformats: DOC MOBI DOT ODT WORDML DOTX FLATOPC EPUB DOCM OTT PS RTF WORD PCL
keywords: JSON в Word, преобразование документов, экспорт JSON, сохранение JSON как DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в WORD через C#" h2="C# API для преобразования JSON в WORD без использования Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете анализировать JSON в WORD в любом приложении .NET, C#, ASP.NET и VB.NET двумя простыми способами. шаги. Во-первых, с помощью [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) вы можете экспортировать JSON в PDF. После этого с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) вы сможете конвертировать PDF в WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в WORD через C#" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) и [Save](https://reference.aspose.com/ Cells/net/aspose.cells.workbook/save/methods/4) в формате PDF
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате WORD, используя метод [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в WORD через С#" %}}
При синтаксическом анализе JSON в WORD вы также можете установить параметры макета для вашего JSON с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать формат JSON в WORD с водяным знаком" %}}
Используя API, вы также можете конвертировать JSON в WORD с водяным знаком. Чтобы добавить водяной знак в ваш документ WORD, вы можете сначала преобразовать файл JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document), создайте экземпляр TextWatermarkOptions и задайте его свойства., Вызовите метод Watermark.SetText и передайте текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в WORD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}