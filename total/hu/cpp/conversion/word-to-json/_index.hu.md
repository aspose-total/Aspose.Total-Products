---
title: A WORD konvertálása JSON formátumba C++ nyelven
description: Exportálja a WORD-t JSON-ba C++-ban Microsoft Excel vagy Word használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="A WORD konvertálása JSON formátumba a C++ segítségével" h2="WORD exportálása JSON-ba C++-on keresztül Microsoft<sup>&reg;</sup> Word vagy Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) használatával konvertálhatja a WORD-t JSON formátumba a C++ alkalmazásaiban. Először is, az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával exportálhatja a WORD-t HTML-be. Ezt követően az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával konvertálhatja a HTML-t JSON formátumba. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A WORD konvertálása JSON formátumba a C++ segítségével" %}}
1. Nyissa meg a WORD-fájlt a [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument) osztályhivatkozás használatával
2. Alakítsa át a WORD-t HTML-vé a [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat) tagfüggvény használatával
3. Töltsön be HTML-dokumentumot az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztályhivatkozás használatával
4. Mentse a dokumentumot JSON formátumba a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paraméterrel.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A védett WORD konvertálása JSON formátumba a C++ segítségével" %}}
Az API segítségével a jelszóval védett dokumentumot is megnyithatja. Ha a bemeneti WORD-dokumentum jelszóval védett, nem konvertálhatja azt JSON-formátumba a jelszó használata nélkül. Ehhez használjon speciális konstruktor túlterhelést, amely elfogad egy LoadOptions objektumot. Ez az objektum tartalmazza a Jelszó tulajdonságot, amely a jelszó karakterláncot adja meg.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}