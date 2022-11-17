---
title: C++ API om PPSX naar DOCM te converteren
description: Exporteer PPSX naar DOCM binnen uw C++-toepassingen

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOCM
otherformats: WORD FLATOPC ODT DOTX DOC DOCX WORDML OTT DOT RTF TEXT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om PPSX naar DOCM te renderen" h2="Exporteer PPSX naar DOCM in C++-toepassingen zonder Microsoft PowerPoint- of Word-afhankelijkheden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) is een compleet pakket van C++ File Format Automation-bibliotheken. Door gebruik te maken van de uitgebreide functies van de API's die beschikbaar zijn in het pakket, kunnen we PowerPoint PPSX gemakkelijk converteren naar Word DOCM. Om de conversie uit te voeren, kunt u eerst de API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om PPSX naar HTML te converteren. Daarna kunt u met behulp van de veelzijdige Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) de HTML naar DOCM converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om PPSX naar DOCM te converteren" %}}
1. Laad PPSX-bestand met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) klassereferentie
2. Render PPSX naar HTML met behulp van [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) lidfunctie en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument) klasseverwijzing
4. Sla het docmument op in DOCM-formaat met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string) lidfunctie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-word/" name="PPSX Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-flatopc/" name="PPSX Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-odt/" name="PPSX Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-dotx/" name="PPSX Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-docm/" name="PPSX Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-docmx/" name="PPSX Tot DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-wordml/" name="PPSX Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-ott/" name="PPSX Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-dot/" name="PPSX Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-rtf/" name="PPSX Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-text/" name="PPSX Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/ppsx-to-dotm/" name="PPSX Tot DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}