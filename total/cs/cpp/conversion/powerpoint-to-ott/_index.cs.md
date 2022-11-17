---
title: C++ API pro převod POWERPOINT na OTT
description: Exportujte POWERPOINT do OTT v rámci vašich aplikací C++

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: OTT
otherformats: DOT WORDML TEXT RTF ODT DOTX FLATOPC DOC DOTM DOCM WORD DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro vykreslení POWERPOINT do OTT" h2="Export POWERPOINT do OTT v aplikacích C++ bez jakýchkoli závislostí Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) je kompletní balíček knihoven C++ File Format Automation. Pomocí bohatých funkcí API dostupných v balíčku můžeme snadno převést PowerPoint POWERPOINT na Word OTT. Chcete-li provést převod, můžete nejprve použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API k převodu POWERPOINT do HTML. Powerpointé pomocí rozhraní API pro zpracování textu s bohatými funkcemi [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete převést HTML na OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod POWERPOINT na OTT" %}}
1. Načtěte soubor POWERPOINT pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Vykreslete POWERPOINT do HTML pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí odkazu na třídu [Ottument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)
4. Uložte dokument ve formátu OTT pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string)
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
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-dot/" name="PPTX Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-wordml/" name="PPTX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-text/" name="PPTX Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-rtf/" name="PPTX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-odt/" name="PPTX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-dotx/" name="PPTX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-flatopc/" name="PPTX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-ott/" name="PPTX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-dotm/" name="PPTX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-ottm/" name="PPTX Na OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-word/" name="PPTX Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/pptx-to-ottx/" name="PPTX Na OTTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}