---
title: C++ API a PPS DOTM formátumba konvertálásához
description: Exportálja a PPS-ot DOTM-ba a C++ alkalmazásaiban

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOTM
otherformats: DOC ODT DOT DOCX DOTX RTF DOCM WORD TEXT WORDML FLATOPC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a PPS rendereléséhez DOTM-ba" h2="Exportálja a PPS-ot DOTM-ba C++ alkalmazásokban Microsoft PowerPoint vagy Word függőség nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) a C++ fájlformátum-automatizálási könyvtárak teljes csomagja. A csomagban elérhető API-k gazdag funkcióinak használatával könnyedén konvertálhatjuk a PowerPoint PPS-ot Word DOTM-ba. Az átalakítás végrehajtásához először használhatja az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API-t a PPS HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával a HTML-t DOTM formátumba konvertálhatja. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a PPS DOTM-vé konvertálásához" %}}
1. Töltse be a PPS-fájlt a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
2. Rendelje meg a PPS-ot HTML-ben a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfunkcióval, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument) osztályhivatkozás használatával
4. Mentse a dokumentumot DOTM formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string) tagfunkcióval
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
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
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-dotm/" name="PPS Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-odt/" name="PPS Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-dot/" name="PPS Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-dotmx/" name="PPS Nak nek DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-dotx/" name="PPS Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-rtf/" name="PPS Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-dotmm/" name="PPS Nak nek DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-word/" name="PPS Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-text/" name="PPS Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-wordml/" name="PPS Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-flatopc/" name="PPS Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pps-to-ott/" name="PPS Nak nek OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}