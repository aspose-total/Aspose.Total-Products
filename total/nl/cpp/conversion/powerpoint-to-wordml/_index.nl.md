---
title: C++ API om POWERPOINT naar WORDML te converteren
description: Exporteer POWERPOINT naar WORDML binnen uw C++-toepassingen
url: /nl/cpp/conversion/powerpoint-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: WORDML
otherformats: RTF DOTX DOT DOCM DOC OTT DOCX FLATOPC TEXT WORD ODT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om POWERPOINT naar WORDML te renderen" h2="Exporteer POWERPOINT naar WORDML in C++-toepassingen zonder Microsoft PowerPoint- of Word-afhankelijkheden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) is een compleet pakket van C++ File Format Automation-bibliotheken. Door gebruik te maken van de uitgebreide functies van de API's die beschikbaar zijn in het pakket, kunnen we PowerPoint POWERPOINT gemakkelijk converteren naar Word WORDML. Om de conversie uit te voeren, kunt u eerst de API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om POWERPOINT naar HTML te converteren. Daarna kunt u met behulp van de veelzijdige Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) de HTML naar WORDML converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om POWERPOINT naar WORDML te converteren" %}}
1. Laad POWERPOINT-bestand met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) klassereferentie
2. Render POWERPOINT naar HTML met behulp van [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) lidfunctie en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met behulp van [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) klasseverwijzing
4. Sla het wordmlument op in WORDML-formaat met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) lidfunctie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-rtf/" name="PPTX Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-dotx/" name="PPTX Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-dot/" name="PPTX Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-wordmlm/" name="PPTX Tot WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-wordml/" name="PPTX Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-ott/" name="PPTX Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-wordmlx/" name="PPTX Tot WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-flatopc/" name="PPTX Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-text/" name="PPTX Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-word/" name="PPTX Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-odt/" name="PPTX Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptx-to-dotm/" name="PPTX Tot DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}