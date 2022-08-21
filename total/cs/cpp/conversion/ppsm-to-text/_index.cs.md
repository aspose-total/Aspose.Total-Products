---
title: C++ API pro převod PPSM na TEXT
description: Exportujte PPSM do TEXT v rámci vašich aplikací C++
url: /cs/cpp/conversion/ppsm-to-text/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: TEXT
otherformats: DOC DOCX ODT FLATOPC DOTX OTT DOCM RTF WORD WORDML DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro vykreslení PPSM do TEXT" h2="Export PPSM do TEXT v aplikacích C++ bez jakýchkoli závislostí Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) je kompletní balíček knihoven C++ File Format Automation. Pomocí bohatých funkcí API dostupných v balíčku můžeme snadno převést PowerPoint PPSM na Word TEXT. Chcete-li provést převod, můžete nejprve použít [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API k převodu PPSM do HTML. Ppsmé pomocí rozhraní API pro zpracování textu s bohatými funkcemi [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete převést HTML na TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod PPSM na TEXT" %}}
1. Načtěte soubor PPSM pomocí odkazu třídy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Vykreslete PPSM do HTML pomocí členské funkce [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí odkazu na třídu [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument)
4. Uložte dokument ve formátu TEXT pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string)
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
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-text/" name="PPSM Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-textx/" name="PPSM Na TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-odt/" name="PPSM Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-flatopc/" name="PPSM Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dotx/" name="PPSM Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-ott/" name="PPSM Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-textm/" name="PPSM Na TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-rtf/" name="PPSM Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-word/" name="PPSM Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-wordml/" name="PPSM Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dotm/" name="PPSM Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/ppsm-to-dot/" name="PPSM Na DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}