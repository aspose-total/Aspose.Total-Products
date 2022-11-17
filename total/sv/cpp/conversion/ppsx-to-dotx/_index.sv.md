---
title: C++ API för att konvertera PPSX till DOTX
description: Exportera PPSX till DOTX i dina C++-applikationer

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOTX
otherformats: DOC DOT TEXT FLATOPC WORD ODT DOCX WORDML RTF DOCM DOTM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att rendera PPSX till DOTX" h2="Exportera PPSX till DOTX i C++-applikationer utan några Microsoft PowerPoint- eller Word-beroenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) är ett komplett paket med C++ filformatsautomatiseringsbibliotek. Genom att använda de rika funktionerna i API:erna som finns i paketet kan vi enkelt konvertera PowerPoint PPSX till Word DOTX. För att utföra konverteringen kan du först använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API för att konvertera PPSX till HTML. Därefter kan du konvertera HTML till DOTX genom att använda funktionsrika Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera PPSX till DOTX" %}}
1. Ladda PPSX-fil med klassreferens [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Återge PPSX till HTML genom att använda [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) medlemsfunktion och ställ in HTML som SaveFormat
3. Ladda den konverterade HTML-filen genom att använda klassreferensen [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
4. Spara dokumentet i DOTX-format genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotxument
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"htmlOutput.html");
// save dotxument in DOTX format
dotx->Save(u"output.dotx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-dotx/" name="PPSX Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-dot/" name="PPSX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-text/" name="PPSX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-flatopc/" name="PPSX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-word/" name="PPSX Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-odt/" name="PPSX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-dotxx/" name="PPSX Till DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-wordml/" name="PPSX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-rtf/" name="PPSX Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-dotxm/" name="PPSX Till DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-dotm/" name="PPSX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppsx-to-ott/" name="PPSX Till OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}