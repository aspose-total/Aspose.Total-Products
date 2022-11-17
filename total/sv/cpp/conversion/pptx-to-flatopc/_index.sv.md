---
title: C++ API för att konvertera PPTX till FLATOPC
description: Exportera PPTX till FLATOPC i dina C++-applikationer

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: FLATOPC
otherformats: TEXT OTT DOCX DOT DOCM DOTM WORDML DOC WORD ODT DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att rendera PPTX till FLATOPC" h2="Exportera PPTX till FLATOPC i C++-applikationer utan några Microsoft PowerPoint- eller Word-beroenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) är ett komplett paket med C++ filformatsautomatiseringsbibliotek. Genom att använda de rika funktionerna i API:erna som finns i paketet kan vi enkelt konvertera PowerPoint PPTX till Word FLATOPC. För att utföra konverteringen kan du först använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API för att konvertera PPTX till HTML. Därefter kan du konvertera HTML till FLATOPC genom att använda funktionsrika Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera PPTX till FLATOPC" %}}
1. Ladda PPTX-fil med klassreferens [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Återge PPTX till HTML genom att använda [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) medlemsfunktion och ställ in HTML som SaveFormat
3. Ladda den konverterade HTML-filen genom att använda klassreferensen [Flatopcument](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument)
4. Spara dokumentet i FLATOPC-format genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-text/" name="PPTX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-ott/" name="PPTX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-flatopcx/" name="PPTX Till FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-dot/" name="PPTX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-flatopcm/" name="PPTX Till FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-dotm/" name="PPTX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-wordml/" name="PPTX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-flatopc/" name="PPTX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-word/" name="PPTX Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-odt/" name="PPTX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-dotx/" name="PPTX Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/pptx-to-rtf/" name="PPTX Till RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}