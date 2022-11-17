---
title: C++ API pro převod PPSX na WORD
description: Exportujte PPSX do WORD v rámci vašich aplikací C++

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOCX
otherformats: WORDML DOCM DOCX DOTM DOC OTT TEXT DOT DOTX ODT FLATOPC RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro vykreslení PPSX do WORD" h2="Export PPSX do WORD v aplikacích C++ bez jakýchkoli závislostí Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) je kompletní balíček knihoven C++ File Format Automation. Pomocí bohatých funkcí API dostupných v balíčku můžeme snadno převést PowerPoint PPSX na Word WORD. Chcete-li provést převod, můžete nejprve použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API k převodu PPSX do HTML. Ppsxé pomocí rozhraní API pro zpracování textu s bohatými funkcemi [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete převést HTML na WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod PPSX na WORD" %}}
1. Načtěte soubor PPSX pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Vykreslete PPSX do HTML pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí odkazu na třídu [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument)
4. Uložte dokument ve formátu WORD pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordument
System::SharedPtr<Wordument> word = System::MakeObject<Wordument>(u"htmlOutput.html");
// save wordument in WORDX format
word->Save(u"output.wordx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-wordml/" name="PPSX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-wordm/" name="PPSX Na WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-wordx/" name="PPSX Na WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-dotm/" name="PPSX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-word/" name="PPSX Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-ott/" name="PPSX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-text/" name="PPSX Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-dot/" name="PPSX Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-dotx/" name="PPSX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-odt/" name="PPSX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-flatopc/" name="PPSX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsx-to-rtf/" name="PPSX Na RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}