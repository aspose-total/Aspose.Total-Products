---
title: C++ API do konwersji PPT na FLATOPC
description: Eksportuj PPT do FLATOPC w swoich aplikacjach C++

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: FLATOPC
otherformats: TEXT OTT WORDML DOTM DOCM DOC WORD DOT DOCX RTF ODT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do renderowania PPT do FLATOPC" h2="Eksportuj PPT do FLATOPC w aplikacjach C++ bez żadnych zależności Microsoft PowerPoint lub Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) to kompletny pakiet bibliotek C++ File Format Automation. Korzystając z bogatych funkcji API dostępnych w pakiecie, możemy łatwo przekonwertować PowerPoint PPT na Word FLATOPC. Aby przeprowadzić konwersję, możesz najpierw użyć interfejsu API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby przekonwertować PPT na HTML. Następnie za pomocą bogatego w funkcje interfejsu API przetwarzania tekstu [Aspose.Words for C++](https://products.aspose.com/words/cpp/) możesz przekonwertować kod HTML na FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji PPT na FLATOPC" %}}
1. Załaduj plik PPT, korzystając z referencji do klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Wyrenderuj PPT do HTML za pomocą funkcji [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Html jako SaveFormat
3. Załaduj przekonwertowany plik HTML, korzystając z odwołania do klasy [Flatopcument](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument)
4. Zapisz dokument w formacie FLATOPC, używając funkcji członka [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
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
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-text/" name="PPT Do TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-ott/" name="PPT Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-wordml/" name="PPT Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-dotm/" name="PPT Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-flatopcm/" name="PPT Do FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-flatopc/" name="PPT Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-word/" name="PPT Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-dot/" name="PPT Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-flatopcx/" name="PPT Do FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-rtf/" name="PPT Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-odt/" name="PPT Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/ppt-to-dotx/" name="PPT Do DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}