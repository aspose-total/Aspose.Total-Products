---
title: C++ API a POTX DOCM formátumba konvertálásához
description: Exportálja a POTX-ot DOCM-ba a C++ alkalmazásaiban
url: /hu/cpp/conversion/potx-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOCM
otherformats: DOT FLATOPC DOC OTT RTF DOTX WORD TEXT DOTM DOCX WORDML ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a POTX rendereléséhez DOCM-ba" h2="Exportálja a POTX-ot DOCM-ba C++ alkalmazásokban Microsoft PowerPoint vagy Word függőség nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) a C++ fájlformátum-automatizálási könyvtárak teljes csomagja. A csomagban elérhető API-k gazdag funkcióinak használatával könnyedén konvertálhatjuk a PowerPoint POTX-ot Word DOCM-ba. Az átalakítás végrehajtásához először használhatja az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API-t a POTX HTML-lé konvertálásához. Ezt követően a funkciókban gazdag szövegszerkesztő API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával a HTML-t DOCM formátumba konvertálhatja. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a POTX DOCM-vé konvertálásához" %}}
1. Töltse be a POTX-fájlt a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztályhivatkozás használatával
2. Rendelje meg a POTX-ot HTML-ben a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) tagfunkcióval, és állítsa be a HTML-t SaveFormat-ként
3. Töltse be a konvertált HTML-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument) osztályhivatkozás használatával
4. Mentse a dokumentumot DOCM formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string) tagfunkcióval
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-dot/" name="POTX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-flatopc/" name="POTX Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-docm/" name="POTX Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-ott/" name="POTX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-rtf/" name="POTX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-dotx/" name="POTX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-word/" name="POTX Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-text/" name="POTX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-dotm/" name="POTX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-docmx/" name="POTX Nak nek DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-wordml/" name="POTX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/potx-to-odt/" name="POTX Nak nek ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}