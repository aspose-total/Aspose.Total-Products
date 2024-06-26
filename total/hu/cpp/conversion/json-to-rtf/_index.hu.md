---
title: Konvertálja a JSON formátumot RTF-re a C++ segítségével
description: C++ API t0 JSON elemzése RTF-re Microsoft Word használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: RTF
otherformats: PCL PS WORD FLATOPC EPUB ODT DOCM OTT WORDML MOBI DOT DOC DOTX CHM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a JSON formátumot RTF-re a C++ segítségével" h2="Elemezze a JSON-t RTF-be a C++ alkalmazásokon belül a Microsoft<sup>&reg;</sup> Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) használatával két egyszerű lépésben elemezheti a JSON-t RTF-be a C++ alkalmazásaiban. Először is, az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával PDF-formátumba exportálhatja a JSON-t. Ezt követően az [Aspose.Words for C++](https://products.aspose.com/words/cppp/) használatával konvertálhatja a PDF-et RTF formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot RTF-re C++ nyelven" %}}
1. Hozzon létre egy új [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Mentse el a JSON fájlt PDF formátumban a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) módszerrel
3. Töltse be a PDF-dokumentumot a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály használatával
4. Mentse a dokumentumot RTF formátumba a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) metódussal
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paraméterrel.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az Elrendezést és konvertálja a JSON-formátumot RTF-re C++-ban" %}}
A JSON RTF-re történő elemzése közben a sorok és oszlopok méretét is beállíthatja az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztály JSON-jának betöltésével. Ha ugyanazt a sormagasságot kell beállítania a munkalap minden sorához, ezt a [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a673f16a673f) segítségével teheti meg. ) módszere az [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) gyűjteményben. Hasonlóképpen, ha a munkalap minden oszlopához azonos oszlopszélességet szeretne beállítani, használja az ICells gyűjtemény [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b7)500094b7 metódusát.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON formátumot RTF-re vízjellel a C++ nyelven" %}}
Az API használatával a JSON-t is elemezheti a RTF-be vízjellel. Ha vízjelet szeretne hozzáadni a RTF-dokumentumhoz, először konvertálja a JSON-t PDF-be, és vízjelet adjon hozzá. Vízjel hozzáadásához töltse be az újonnan létrehozott PDF-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztály segítségével, állítson be különböző tulajdonságokat a szöveges vízjelhez,
hívja meg a SetText metódust, és adja át a vízjel szövegét és a TextWatermarkOptions objektumát. A vízjel hozzáadása után a dokumentumot elmentheti a RTF-be.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}