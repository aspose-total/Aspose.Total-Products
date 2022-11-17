---
title: C++ API pro převod PPSM na DOTM
description: Exportujte PPSM do DOTM v rámci vašich aplikací C++

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOTM
otherformats: WORDML DOT WORD DOTX ODT TEXT OTT DOC DOCM DOCX RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro vykreslení PPSM do DOTM" h2="Export PPSM do DOTM v aplikacích C++ bez jakýchkoli závislostí Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) je kompletní balíček knihoven C++ File Format Automation. Pomocí bohatých funkcí API dostupných v balíčku můžeme snadno převést PowerPoint PPSM na Word DOTM. Chcete-li provést převod, můžete nejprve použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API k převodu PPSM do HTML. Ppsmé pomocí rozhraní API pro zpracování textu s bohatými funkcemi [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete převést HTML na DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod PPSM na DOTM" %}}
1. Načtěte soubor PPSM pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Vykreslete PPSM do HTML pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí odkazu na třídu [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
4. Uložte dokument ve formátu DOTM pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsm");
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
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-wordml/" name="PPSM Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dot/" name="PPSM Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-word/" name="PPSM Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dotx/" name="PPSM Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-odt/" name="PPSM Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-text/" name="PPSM Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-ott/" name="PPSM Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dotm/" name="PPSM Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dotmm/" name="PPSM Na DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dotmx/" name="PPSM Na DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-rtf/" name="PPSM Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-flatopc/" name="PPSM Na FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}