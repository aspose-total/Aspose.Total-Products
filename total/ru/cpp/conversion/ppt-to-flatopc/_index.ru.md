---
title: C++ API для преобразования PPT в FLATOPC
description: Экспорт PPT в FLATOPC в ваших приложениях C++

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: FLATOPC
otherformats: TEXT OTT WORDML DOTM DOCM DOC WORD DOT DOCX RTF ODT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для рендеринга PPT в FLATOPC" h2="Экспорт PPT в FLATOPC в приложениях C++ без каких-либо зависимостей от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) — это полный пакет библиотек C++ File Format Automation. Используя богатые возможности API-интерфейсов, доступных в пакете, мы можем легко преобразовать PowerPoint PPT в Word FLATOPC. Чтобы выполнить преобразование, вы можете сначала использовать API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) для преобразования PPT в HTML. После этого с помощью многофункционального API обработки текстов [Aspose.Words for C++](https://products.aspose.com/words/cpp/) вы можете конвертировать HTML в FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования PPT в FLATOPC" %}}
1. Загрузите файл PPT, используя ссылку на класс [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Преобразуйте PPT в HTML, используя функцию члена [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Html как SaveFormat.
3. Загрузите преобразованный HTML-файл, используя ссылку на класс [Flatopcument](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument).
4. Сохраните документ в формате FLATOPC, используя функцию члена [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_string).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Flatopcument
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"htmlOutput.html");
// save flatopcument in FLATOPC format
flatopc->Save(u"output.flatopc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-text/" name="PPT К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-ott/" name="PPT К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-wordml/" name="PPT К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-dotm/" name="PPT К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-flatopcm/" name="PPT К FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-flatopc/" name="PPT К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-word/" name="PPT К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-dot/" name="PPT К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-flatopcx/" name="PPT К FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-rtf/" name="PPT К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-odt/" name="PPT К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/ppt-to-dotx/" name="PPT К DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}