---
title: Konvertálja a DOC-t TSV-vé C++-ban vagy ingyenes online konverterrel
description: C++ API a DOC konvertálásához TSV-vé Microsoft Word vagy Microsoft Excel használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes POT-CSV online konvertert.

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: TSV
otherformats: SXC XLS XLSX CSV EXCEL DIF XLTX XLAM XLSM XLTM FODS XLSB ODS XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a DOC TSV-vé konvertálásához vagy Online App" h2="DOC exportálása TSV-be C++-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Könnyedén beépíthet DOC-tsv-átalakítási funkciót C++-alkalmazásaiba. A funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával DOC-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával konvertálhatja a HTML-t TSV-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a DOC TSV-vé konvertálásához vagy Online App" %}}
1. Nyissa meg a DOC-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozás használatával
2. Alakítsa át a DOC-t HTML-vé a [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) tagfüggvény használatával
3. Töltsön be HTML-dokumentumot az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztályhivatkozás használatával
4. Mentse el a dokumentumot TSV formátumba a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a DOC dokumentum tulajdonságait a C++ segítségével" %}}
Az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) emellett lehetővé teszi a DOC-fájl dokumentumtulajdonságaihoz való hozzáférést, és lehetővé teszi, hogy tájékozott döntést hozzon az átalakítási folyamat előtt. A dokumentumtulajdonságok eléréséhez a [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) segítségével szerezheti be a beépített tulajdonságokat és a [CustomDocumentProperties]( reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) egyéni tulajdonságok beszerzéséhez. A következő kódpélda bemutatja, hogyan kell felsorolni az összes beépített és egyéni tulajdonságot egy dokumentumban.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mentse el a TSV-fájlt a Streambe C++-on keresztül" %}}
A DOC TSV-vé konvertálása után az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) lehetővé teszi a dokumentum adatfolyamba való mentését. Fájlok adatfolyamba mentéséhez hozzon létre egy MemoryStream vagy FileStream objektumot, és mentse a fájlt az adatfolyam objektumba az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) meghívásával. az objektum [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) metódusával. Adja meg a kívánt fájlformátumot a [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) felsorolással a [Save](https://reference.aspose.) meghívásakor módszerrel.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-sxc/" name="DOC Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xls/" name="DOC Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xlsx/" name="DOC Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-tsv/" name="DOC Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-excel/" name="DOC Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-dif/" name="DOC Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xltx/" name="DOC Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xlam/" name="DOC Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xlsm/" name="DOC Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xltm/" name="DOC Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-fods/" name="DOC Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xlsb/" name="DOC Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-ods/" name="DOC Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/doc-to-xlt/" name="DOC Nak nek XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}