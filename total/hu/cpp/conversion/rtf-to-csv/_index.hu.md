---
title: Konvertálja a RTF-t CSV-vé C++-ban vagy ingyenes online konverterrel
description: C++ API a RTF konvertálásához CSV-vé Microsoft Word vagy Microsoft Excel használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes POT-CSV online konvertert.

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: CSV
otherformats: XLSM XLSX EXCEL XLTX XLAM SXC FODS XLSB DIF XLT XLS TSV ODS XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a RTF CSV-vé konvertálásához vagy Online App" h2="RTF exportálása CSV-be C++-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Könnyedén beépíthet RTF-csv-átalakítási funkciót C++-alkalmazásaiba. A funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával RTF-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával konvertálhatja a HTML-t CSV-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a RTF CSV-vé konvertálásához vagy Online App" %}}
1. Nyissa meg a RTF-fájlt a [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument) osztályhivatkozás használatával
2. Alakítsa át a RTF-t HTML-vé a [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string_saveformat) tagfüggvény használatával
3. Töltsön be HTML-dokumentumot az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztályhivatkozás használatával
4. Mentse el a dokumentumot CSV formátumba a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a RTF dokumentum tulajdonságait a C++ segítségével" %}}
Az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) emellett lehetővé teszi a RTF-fájl dokumentumtulajdonságaihoz való hozzáférést, és lehetővé teszi, hogy tájékozott döntést hozzon az átalakítási folyamat előtt. A dokumentumtulajdonságok eléréséhez a [BuiltInRtfumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_rtfument_properties) segítségével szerezheti be a beépített tulajdonságokat és a [CustomRtfumentProperties]( reference.aspose.com/words/cpp/class/aspose.words.properties.custom_rtfument_properties) egyéni tulajdonságok beszerzéséhez. A következő kódpélda bemutatja, hogyan kell felsorolni az összes beépített és egyéni tulajdonságot egy dokumentumban.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-rtfument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mentse el a CSV-fájlt a Streambe C++-on keresztül" %}}
A RTF CSV-vé konvertálása után az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) lehetővé teszi a dokumentum adatfolyamba való mentését. Fájlok adatfolyamba mentéséhez hozzon létre egy MemoryStream vagy FileStream objektumot, és mentse a fájlt az adatfolyam objektumba az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) meghívásával. az objektum [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) metódusával. Adja meg a kívánt fájlformátumot a [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) felsorolással a [Save](https://reference.aspose.) meghívásakor módszerrel.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xlsm/" name="RTF Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xlsx/" name="RTF Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-excel/" name="RTF Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xltx/" name="RTF Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xlam/" name="RTF Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-sxc/" name="RTF Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-fods/" name="RTF Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xlsb/" name="RTF Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-dif/" name="RTF Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xlt/" name="RTF Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xls/" name="RTF Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-tsv/" name="RTF Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-ods/" name="RTF Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/rtf-to-xltm/" name="RTF Nak nek XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}