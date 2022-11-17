---
title: C++ API om PPTM naar DOC te converteren
description: Exporteer PPTM naar DOC binnen uw C++-toepassingen

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: DOC
otherformats: FLATOPC OTT DOTM RTF ODT DOCX DOTX DOCM WORDML DOT WORD TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API om PPTM naar DOC te renderen" h2="Exporteer PPTM naar DOC in C++-toepassingen zonder Microsoft PowerPoint- of Word-afhankelijkheden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) is een compleet pakket van C++ File Format Automation-bibliotheken. Door gebruik te maken van de uitgebreide functies van de API's die beschikbaar zijn in het pakket, kunnen we PowerPoint PPTM gemakkelijk converteren naar Word DOC. Om de conversie uit te voeren, kunt u eerst de API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) gebruiken om PPTM naar HTML te converteren. Daarna kunt u met behulp van de veelzijdige Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) de HTML naar DOC converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API om PPTM naar DOC te converteren" %}}
1. Laad PPTM-bestand met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) klassereferentie
2. Render PPTM naar HTML met behulp van [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) lidfunctie en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met behulp van [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klasseverwijzing
4. Sla het document op in DOC-formaat met behulp van [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string) lidfunctie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-flatopc/" name="PPTM Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-ott/" name="PPTM Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-dotm/" name="PPTM Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-rtf/" name="PPTM Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-odt/" name="PPTM Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-docx/" name="PPTM Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-dotx/" name="PPTM Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-docm/" name="PPTM Tot DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-wordml/" name="PPTM Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-dot/" name="PPTM Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-word/" name="PPTM Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/cpp/conversion/pptm-to-text/" name="PPTM Tot TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}