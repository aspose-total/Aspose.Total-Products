---
title: C++ API для преобразования POWERPOINT в WORDML
description: Экспорт POWERPOINT в WORDML в ваших приложениях C++

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: WORDML
otherformats: RTF DOTX DOT DOCM DOC OTT DOCX FLATOPC TEXT WORD ODT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для рендеринга POWERPOINT в WORDML" h2="Экспорт POWERPOINT в WORDML в приложениях C++ без каких-либо зависимостей от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) — это полный пакет библиотек C++ File Format Automation. Используя богатые возможности API-интерфейсов, доступных в пакете, мы можем легко преобразовать PowerPoint POWERPOINT в Word WORDML. Чтобы выполнить преобразование, вы можете сначала использовать API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) для преобразования POWERPOINT в HTML. После этого с помощью многофункционального API обработки текстов [Aspose.Words for C++](https://products.aspose.com/words/cpp/) вы можете конвертировать HTML в WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования POWERPOINT в WORDML" %}}
1. Загрузите файл POWERPOINT, используя ссылку на класс [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Преобразуйте POWERPOINT в HTML, используя функцию члена [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Html как SaveFormat.
3. Загрузите преобразованный HTML-файл, используя ссылку на класс [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument).
4. Сохраните документ в формате WORDML, используя функцию члена [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POWERPOINT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-rtf/" name="PPTX К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-dotx/" name="PPTX К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-dot/" name="PPTX К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-wordmlm/" name="PPTX К WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-wordml/" name="PPTX К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-ott/" name="PPTX К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-wordmlx/" name="PPTX К WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-flatopc/" name="PPTX К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-text/" name="PPTX К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-word/" name="PPTX К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-odt/" name="PPTX К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptx-to-dotm/" name="PPTX К DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}