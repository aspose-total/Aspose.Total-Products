---
title: C++ API do konwersji PPTX na OTT
description: Eksportuj PPTX do OTT w swoich aplikacjach C++
url: /pl/cpp/conversion/pptx-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: OTT
otherformats: TEXT DOCX WORD WORDML DOC DOT DOCM DOTX ODT RTF FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do renderowania PPTX do OTT" h2="Eksportuj PPTX do OTT w aplikacjach C++ bez żadnych zależności Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) to kompletny pakiet bibliotek C++ File Format Automation. Korzystając z bogatych funkcji API dostępnych w pakiecie, możemy łatwo przekonwertować PowerPoint PPTX na Word OTT. Aby przeprowadzić konwersję, możesz najpierw użyć interfejsu API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby przekonwertować PPTX na HTML. Następnie za pomocą bogatego w funkcje interfejsu API przetwarzania tekstu [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz przekonwertować kod HTML na OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji PPTX na OTT" %}}
1. Załaduj plik PPTX, korzystając z referencji do klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Wyrenderuj PPTX do HTML za pomocą funkcji [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Html jako SaveFormat
3. Załaduj przekonwertowany plik HTML, korzystając z odwołania do klasy [Ottument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)
4. Zapisz dokument w formacie OTT, używając funkcji członka [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-text/" name="PPTX Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-ottx/" name="PPTX Do OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-word/" name="PPTX Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-wordml/" name="PPTX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-ott/" name="PPTX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-dot/" name="PPTX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-ottm/" name="PPTX Do OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-dotx/" name="PPTX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-odt/" name="PPTX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-rtf/" name="PPTX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-flatopc/" name="PPTX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/pptx-to-dotm/" name="PPTX Do DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}