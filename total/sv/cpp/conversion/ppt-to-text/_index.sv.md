---
title: C++ API för att konvertera PPT till TEXT
description: Exportera PPT till TEXT i dina C++-applikationer

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: TEXT
otherformats: OTT ODT DOC DOTX FLATOPC DOCM DOCX DOT RTF WORDML WORD DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att rendera PPT till TEXT" h2="Exportera PPT till TEXT i C++-applikationer utan några Microsoft PowerPoint- eller Word-beroenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) är ett komplett paket med C++ filformatsautomatiseringsbibliotek. Genom att använda de rika funktionerna i API:erna som finns i paketet kan vi enkelt konvertera PowerPoint PPT till Word TEXT. För att utföra konverteringen kan du först använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API för att konvertera PPT till HTML. Därefter kan du konvertera HTML till TEXT genom att använda funktionsrika Word Processing API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera PPT till TEXT" %}}
1. Ladda PPT-fil med klassreferens [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Återge PPT till HTML genom att använda [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) medlemsfunktion och ställ in HTML som SaveFormat
3. Ladda den konverterade HTML-filen genom att använda klassreferensen [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument)
4. Spara dokumentet i TEXT-format genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-ott/" name="PPT Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-odt/" name="PPT Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-text/" name="PPT Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-dotx/" name="PPT Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-flatopc/" name="PPT Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-textm/" name="PPT Till TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-textx/" name="PPT Till TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-dot/" name="PPT Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-rtf/" name="PPT Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-wordml/" name="PPT Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-word/" name="PPT Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/ppt-to-dotm/" name="PPT Till DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}