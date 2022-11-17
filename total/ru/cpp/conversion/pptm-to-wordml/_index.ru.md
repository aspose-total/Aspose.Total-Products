---
title: C++ API для преобразования PPTM в WORDML
description: Экспорт PPTM в WORDML в ваших приложениях C++

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: WORDML
otherformats: DOC DOTM DOCM DOT DOCX WORD FLATOPC TEXT ODT OTT RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для рендеринга PPTM в WORDML" h2="Экспорт PPTM в WORDML в приложениях C++ без каких-либо зависимостей от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) — это полный пакет библиотек C++ File Format Automation. Используя богатые возможности API-интерфейсов, доступных в пакете, мы можем легко преобразовать PowerPoint PPTM в Word WORDML. Чтобы выполнить преобразование, вы можете сначала использовать API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) для преобразования PPTM в HTML. После этого с помощью многофункционального API обработки текстов [Aspose.Words for C++](https://products.aspose.com/words/cpp/) вы можете конвертировать HTML в WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования PPTM в WORDML" %}}
1. Загрузите файл PPTM, используя ссылку на класс [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Преобразуйте PPTM в HTML, используя функцию члена [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Html как SaveFormat.
3. Загрузите преобразованный HTML-файл, используя ссылку на класс [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument).
4. Сохраните документ в формате WORDML, используя функцию члена [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-wordml/" name="PPTM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-dotm/" name="PPTM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-wordmlm/" name="PPTM К WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-dot/" name="PPTM К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-wordmlx/" name="PPTM К WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-word/" name="PPTM К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-flatopc/" name="PPTM К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-text/" name="PPTM К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-odt/" name="PPTM К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-ott/" name="PPTM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-rtf/" name="PPTM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/pptm-to-dotx/" name="PPTM К DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}