---
title: C++ API для преобразования POTX в DOC
description: Экспорт POTX в DOC в ваших приложениях C++

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOC
otherformats: TEXT OTT RTF WORDML ODT DOTM FLATOPC DOCM DOT DOCX DOTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для рендеринга POTX в DOC" h2="Экспорт POTX в DOC в приложениях C++ без каких-либо зависимостей от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) — это полный пакет библиотек C++ File Format Automation. Используя богатые возможности API-интерфейсов, доступных в пакете, мы можем легко преобразовать PowerPoint POTX в Word DOC. Чтобы выполнить преобразование, вы можете сначала использовать API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) для преобразования POTX в HTML. После этого с помощью многофункционального API обработки текстов [Aspose.Words for C++](https://products.aspose.com/words/cpp/) вы можете конвертировать HTML в DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования POTX в DOC" %}}
1. Загрузите файл POTX, используя ссылку на класс [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Преобразуйте POTX в HTML, используя функцию члена [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Html как SaveFormat.
3. Загрузите преобразованный HTML-файл, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Сохраните документ в формате DOC, используя функцию члена [Сохранить](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOC format
doc->Save(u"output.doc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-text/" name="POTX К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-ott/" name="POTX К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-rtf/" name="POTX К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-wordml/" name="POTX К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-odt/" name="POTX К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-dotm/" name="POTX К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-flatopc/" name="POTX К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-docm/" name="POTX К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-dot/" name="POTX К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-docx/" name="POTX К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-dotx/" name="POTX К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/potx-to-word/" name="POTX К WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}