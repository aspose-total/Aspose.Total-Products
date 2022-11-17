---
title: C++ API för att konvertera POTX till DOTM
description: Exportera POTX till DOTM i dina C++-applikationer

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOTM
otherformats: OTT DOT WORDML TEXT DOC FLATOPC DOCX ODT WORD RTF DOCM DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att rendera POTX till DOTM" h2="Exportera POTX till DOTM i C++-applikationer utan några Microsoft PowerPoint- eller Word-beroenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) är ett komplett paket med C++ filformatsautomatiseringsbibliotek. Genom att använda de rika funktionerna i API:erna som finns i paketet kan vi enkelt konvertera PowerPoint POTX till Word DOTM. För att utföra konverteringen kan du först använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API för att konvertera POTX till HTML. Därefter kan du konvertera HTML till DOTM genom att använda funktionsrika Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera POTX till DOTM" %}}
1. Ladda POTX-fil med klassreferens [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Återge POTX till HTML genom att använda [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) medlemsfunktion och ställ in HTML som SaveFormat
3. Ladda den konverterade HTML-filen genom att använda klassreferensen [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
4. Spara dokumentet i DOTM-format genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotmument
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"htmlOutput.html");
// save dotmument in DOTM format
dotm->Save(u"output.dotm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-ott/" name="POTX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-dot/" name="POTX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-wordml/" name="POTX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-text/" name="POTX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-dotm/" name="POTX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-flatopc/" name="POTX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-dotmx/" name="POTX Till DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-odt/" name="POTX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-word/" name="POTX Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-rtf/" name="POTX Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-dotmm/" name="POTX Till DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/potx-to-dotx/" name="POTX Till DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}