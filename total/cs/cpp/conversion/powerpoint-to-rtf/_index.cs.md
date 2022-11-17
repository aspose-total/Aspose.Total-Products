---
title: C++ API pro převod POWERPOINT na RTF
description: Exportujte POWERPOINT do RTF v rámci vašich aplikací C++

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: RTF
otherformats: WORD WORDML DOCX TEXT DOC ODT OTT FLATOPC DOTX DOCM DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro vykreslení POWERPOINT do RTF" h2="Export POWERPOINT do RTF v aplikacích C++ bez jakýchkoli závislostí Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) je kompletní balíček knihoven C++ File Format Automation. Pomocí bohatých funkcí API dostupných v balíčku můžeme snadno převést PowerPoint POWERPOINT na Word RTF. Chcete-li provést převod, můžete nejprve použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API k převodu POWERPOINT do HTML. Powerpointé pomocí rozhraní API pro zpracování textu s bohatými funkcemi [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete převést HTML na RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod POWERPOINT na RTF" %}}
1. Načtěte soubor POWERPOINT pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Vykreslete POWERPOINT do HTML pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí odkazu na třídu [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
4. Uložte dokument ve formátu RTF pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POWERPOINT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-word/" name="PPTX Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-wordml/" name="PPTX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-rtfx/" name="PPTX Na RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-text/" name="PPTX Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-rtf/" name="PPTX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-odt/" name="PPTX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-ott/" name="PPTX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-flatopc/" name="PPTX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-dotx/" name="PPTX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-rtfm/" name="PPTX Na RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-dotm/" name="PPTX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-dot/" name="PPTX Na DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}