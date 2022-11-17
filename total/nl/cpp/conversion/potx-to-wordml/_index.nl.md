---
title: C++ API om POTX naar WORDML te converteren
description: Exporteer POTX naar WORDML binnen uw C++-toepassingen

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: WORDML
otherformats: WORD DOT DOTX DOCX OTT DOCM DOC ODT TEXT FLATOPC DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om POTX naar WORDML te renderen" h2="Exporteer POTX naar WORDML in C++-toepassingen zonder Microsoft PowerPoint- of Word-afhankelijkheden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) is een compleet pakket van C++ File Format Automation-bibliotheken. Door gebruik te maken van de uitgebreide functies van de API's die beschikbaar zijn in het pakket, kunnen we PowerPoint POTX gemakkelijk converteren naar Word WORDML. Om de conversie uit te voeren, kunt u eerst de API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om POTX naar HTML te converteren. Daarna kunt u met behulp van de veelzijdige Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) de HTML naar WORDML converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om POTX naar WORDML te converteren" %}}
1. Laad POTX-bestand met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) klassereferentie
2. Render POTX naar HTML met behulp van [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) lidfunctie en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met behulp van [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) klasseverwijzing
4. Sla het wordmlument op in WORDML-formaat met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) lidfunctie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-word/" name="POTX Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-dot/" name="POTX Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-dotx/" name="POTX Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-wordmlx/" name="POTX Tot WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-ott/" name="POTX Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-wordmlm/" name="POTX Tot WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-wordml/" name="POTX Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-odt/" name="POTX Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-text/" name="POTX Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-flatopc/" name="POTX Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-dotm/" name="POTX Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/potx-to-rtf/" name="POTX Tot RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}