---
title: C++ API a POTM ODT formátumba konvertálásához
description: Exportálja a POTM-ot ODT-ba a C++ alkalmazásaiban

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: ODT
otherformats: DOTM DOCX RTF DOTX FLATOPC WORD DOCM DOC WORDML DOT OTT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a POTM rendereléséhez ODT-ba" h2="Exportálja a POTM-ot ODT-ba C++ alkalmazásokban Microsoft PowerPoint vagy Word függőség nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) a C++ fájlformátum-automatizálási könyvtárak teljes csomagja. A csomagban elérhető API-k gazdag funkcióinak használatával könnyedén konvertálhatjuk a PowerPoint POTM-ot Word ODT-ba. Az átalakítás végrehajtásához először használhatja az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API-t a POTM HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával a HTML-t ODT formátumba konvertálhatja. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a POTM ODT-vé konvertálásához" %}}
1. Töltse be a POTM-fájlt a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
2. Rendelje meg a POTM-ot HTML-ben a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfunkcióval, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument) osztályhivatkozás használatával
4. Mentse a dokumentumot ODT formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string) tagfunkcióval
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-dotm/" name="POTM Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-odtx/" name="POTM Nak nek ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-rtf/" name="POTM Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-dotx/" name="POTM Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-flatopc/" name="POTM Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-word/" name="POTM Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-odtm/" name="POTM Nak nek ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-odt/" name="POTM Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-wordml/" name="POTM Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-dot/" name="POTM Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-ott/" name="POTM Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potm-to-text/" name="POTM Nak nek TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}