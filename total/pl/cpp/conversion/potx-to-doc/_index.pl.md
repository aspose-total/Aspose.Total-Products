---
title: C++ API do konwersji POTX na DOC
description: Eksportuj POTX do DOC w swoich aplikacjach C++

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOC
otherformats: TEXT OTT RTF WORDML ODT DOTM FLATOPC DOCM DOT DOCX DOTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do renderowania POTX do DOC" h2="Eksportuj POTX do DOC w aplikacjach C++ bez żadnych zależności Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) to kompletny pakiet bibliotek C++ File Format Automation. Korzystając z bogatych funkcji API dostępnych w pakiecie, możemy łatwo przekonwertować PowerPoint POTX na Word DOC. Aby przeprowadzić konwersję, możesz najpierw użyć interfejsu API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby przekonwertować POTX na HTML. Następnie za pomocą bogatego w funkcje interfejsu API przetwarzania tekstu [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz przekonwertować kod HTML na DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji POTX na DOC" %}}
1. Załaduj plik POTX, korzystając z referencji do klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Wyrenderuj POTX do HTML za pomocą funkcji [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Html jako SaveFormat
3. Załaduj przekonwertowany plik HTML, korzystając z odwołania do klasy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Zapisz dokument w formacie DOC, używając funkcji członka [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
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
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-text/" name="POTX Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-ott/" name="POTX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-rtf/" name="POTX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-wordml/" name="POTX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-odt/" name="POTX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-dotm/" name="POTX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-flatopc/" name="POTX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-docm/" name="POTX Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-dot/" name="POTX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-docx/" name="POTX Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-dotx/" name="POTX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/potx-to-word/" name="POTX Do WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}