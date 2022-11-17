---
title: C++ API a POWERPOINT ODT formátumba konvertálásához
description: Exportálja a POWERPOINT-ot ODT-ba a C++ alkalmazásaiban

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: ODT
otherformats: DOTM DOC WORD DOCM DOCX WORDML DOT RTF TEXT FLATOPC OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a POWERPOINT rendereléséhez ODT-ba" h2="Exportálja a POWERPOINT-ot ODT-ba C++ alkalmazásokban Microsoft PowerPoint vagy Word függőség nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) a C++ fájlformátum-automatizálási könyvtárak teljes csomagja. A csomagban elérhető API-k gazdag funkcióinak használatával könnyedén konvertálhatjuk a PowerPoint POWERPOINT-ot Word ODT-ba. Az átalakítás végrehajtásához először használhatja az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API-t a POWERPOINT HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával a HTML-t ODT formátumba konvertálhatja. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a POWERPOINT ODT-vé konvertálásához" %}}
1. Töltse be a POWERPOINT-fájlt a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
2. Rendelje meg a POWERPOINT-ot HTML-ben a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfunkcióval, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument) osztályhivatkozás használatával
4. Mentse a dokumentumot ODT formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string) tagfunkcióval
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POWERPOINT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-dotm/" name="PPTX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-odt/" name="PPTX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-word/" name="PPTX Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-odtm/" name="PPTX Nak nek ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-odtx/" name="PPTX Nak nek ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-wordml/" name="PPTX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-dot/" name="PPTX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-rtf/" name="PPTX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-text/" name="PPTX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-flatopc/" name="PPTX Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-ott/" name="PPTX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/pptx-to-dotx/" name="PPTX Nak nek DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}