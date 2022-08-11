---
title: C++ API do konwersji PPTM na TEXT
description: Eksportuj PPTM do TEXT w swoich aplikacjach C++
url: /pl/cpp/conversion/pptm-to-text/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: TEXT
otherformats: FLATOPC DOCX DOTM DOTX ODT WORD DOCM OTT RTF WORDML DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do renderowania PPTM do TEXT" h2="Eksportuj PPTM do TEXT w aplikacjach C++ bez żadnych zależności Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) to kompletny pakiet bibliotek C++ File Format Automation. Korzystając z bogatych funkcji API dostępnych w pakiecie, możemy łatwo przekonwertować PowerPoint PPTM na Word TEXT. Aby przeprowadzić konwersję, możesz najpierw użyć interfejsu API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby przekonwertować PPTM na HTML. Następnie za pomocą bogatego w funkcje interfejsu API przetwarzania tekstu [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz przekonwertować kod HTML na TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji PPTM na TEXT" %}}
1. Załaduj plik PPTM, korzystając z referencji do klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Wyrenderuj PPTM do HTML za pomocą funkcji [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Html jako SaveFormat
3. Załaduj przekonwertowany plik HTML, korzystając z odwołania do klasy [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument)
4. Zapisz dokument w formacie TEXT, używając funkcji członka [Save](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-flatopc/" name="PPTM Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-textx/" name="PPTM Do TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-dotm/" name="PPTM Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-dotx/" name="PPTM Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-odt/" name="PPTM Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-word/" name="PPTM Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-textm/" name="PPTM Do TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-ott/" name="PPTM Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-rtf/" name="PPTM Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-wordml/" name="PPTM Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-text/" name="PPTM Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptm-to-dot/" name="PPTM Do DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}