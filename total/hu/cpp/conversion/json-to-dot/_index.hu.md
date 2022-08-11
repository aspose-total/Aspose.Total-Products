---
title: Konvertálja a JSON formátumot DOT-re a C++ segítségével
description: C++ API t0 JSON elemzése DOT-re Microsoft Word használata nélkül
url: /hu/cpp/conversion/json-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOT
otherformats: CHM WORDML OTT ODT PS MOBI WORD DOTX RTF DOC DOCM FLATOPC EPUB PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a JSON formátumot DOT-re a C++ segítségével" h2="Elemezze a JSON-t DOT-be a C++ alkalmazásokon belül a Microsoft<sup>&reg;</sup> Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) használatával két egyszerű lépésben elemezheti a JSON-t DOT-be a C++ alkalmazásaiban. Először is, az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával PDF-formátumba exportálhatja a JSON-t. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cppp/) használatával konvertálhatja a PDF-et DOT formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot DOT-re C++ nyelven" %}}
1. Hozzon létre egy új [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Mentse el a JSON fájlt PDF formátumban a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) módszerrel
3. Töltse be a PDF-dokumentumot a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot DOT formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paraméterrel.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az Elrendezést és konvertálja a JSON-formátumot DOT-re C++-ban" %}}
A JSON DOT-re történő elemzése közben a sorok és oszlopok méretét is beállíthatja az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztály JSON-jának betöltésével. Ha ugyanazt a sormagasságot kell beállítania a munkalap minden sorához, ezt a [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a673f16a673f) segítségével teheti meg. ) módszere az [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) gyűjteményben. Hasonlóképpen, ha a munkalap minden oszlopához azonos oszlopszélességet szeretne beállítani, használja az ICells gyűjtemény [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b7)500094b7 metódusát.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON formátumot DOT-re vízjellel a C++ nyelven" %}}
Az API használatával a JSON-t is elemezheti a DOT-be vízjellel. Ha vízjelet szeretne hozzáadni a DOT-dokumentumhoz, először konvertálja a JSON-t PDF-be, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott PDF-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály segítségével, állítson be különböző tulajdonságokat a szöveges vízjelhez,
hívja meg a SetText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát. A vízjel hozzáadása után a dokumentumot elmentheti a DOT-be.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-dot/" name="JSON Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-wordml/" name="JSON Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-ott/" name="JSON Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-odt/" name="JSON Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-ps/" name="JSON Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-mobi/" name="JSON Nak nek MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-word/" name="JSON Nak nek WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-dotx/" name="JSON Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-rtf/" name="JSON Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-doc/" name="JSON Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-docm/" name="JSON Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-flatopc/" name="JSON Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-epub/" name="JSON Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/json-to-pcl/" name="JSON Nak nek PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}