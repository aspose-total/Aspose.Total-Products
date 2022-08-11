---
title: C++ API a PPT WORDML formátumba konvertálásához
description: Exportálja a PPT-ot WORDML-ba a C++ alkalmazásaiban
url: /hu/cpp/conversion/ppt-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: WORDML
otherformats: DOCM WORD DOTM OTT FLATOPC ODT DOT DOC TEXT DOTX DOCX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a PPT rendereléséhez WORDML-ba" h2="Exportálja a PPT-ot WORDML-ba C++ alkalmazásokban Microsoft PowerPoint vagy Word függőség nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) a C++ fájlformátum-automatizálási könyvtárak teljes csomagja. A csomagban elérhető API-k gazdag funkcióinak használatával könnyedén konvertálhatjuk a PowerPoint PPT-ot Word WORDML-ba. Az átalakítás végrehajtásához először használhatja az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API-t a PPT HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával a HTML-t WORDML formátumba konvertálhatja. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a PPT WORDML-vé konvertálásához" %}}
1. Töltse be a PPT-fájlt a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
2. Rendelje meg a PPT-ot HTML-ben a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfunkcióval, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) osztályhivatkozás használatával
4. Mentse a dokumentumot WORDML formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) tagfunkcióval
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-wordmlm/" name="PPT Nak nek WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-word/" name="PPT Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-dotm/" name="PPT Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-ott/" name="PPT Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-flatopc/" name="PPT Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-odt/" name="PPT Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-dot/" name="PPT Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-wordml/" name="PPT Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-text/" name="PPT Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-dotx/" name="PPT Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-wordmlx/" name="PPT Nak nek WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/ppt-to-rtf/" name="PPT Nak nek RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}