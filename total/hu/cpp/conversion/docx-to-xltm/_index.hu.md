---
title: Konvertálja a DOCX-t XLTM-vé C++-ban
description: C++ API a DOCX konvertálásához XLTM-vé Microsoft Word vagy Microsoft Excel használata nélkül
url: /hu/cpp/conversion/docx-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLTM
otherformats: EXCEL XLTX TSV XLSB XLT XLS DIF FODS CSV XLAM SXC XLSX ODS XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a DOCX XLTM-vé konvertálásához" h2="DOCX exportálása XLTM-be C++-on keresztül Microsoft<sup>&reg;</sup> Word vagy Microsoft<sup>&reg;</sup> Excel használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Könnyedén beépíthet DOCX-xltm-átalakítási funkciót C++-alkalmazásaiba. A funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) használatával DOCX-t HTML-be exportálhat. Ezt követően az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával konvertálhatja a HTML-t XLTM-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a DOCX XLTM-vé konvertálásához" %}}
1. Nyissa meg a DOCX-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) osztályhivatkozás használatával
2. Alakítsa át a DOCX-t HTML-vé a [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) tagfüggvény használatával
3. Töltsön be HTML-dokumentumot az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztályhivatkozás használatával
4. Mentse el a dokumentumot XLTM formátumba a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nyissa meg a DOCX dokumentum tulajdonságait a C++ segítségével" %}}DocumentDocument
Az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) emellett lehetővé teszi a DOCX-fájl dokumentumtulajdonságaihoz való hozzáférést, és lehetővé teszi, hogy tájékozott döntést hozzon az átalakítási folyamat előtt. A dokumentumtulajdonságok eléréséhez a [BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) segítségével szerezheti be a beépített tulajdonságokat és a [CustomDocxumentProperties]( reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) egyéni tulajdonságok beszerzéséhez. A következő kódpélda bemutatja, hogyan kell felsorolni az összes beépített és egyéni tulajdonságot egy dokumentumban.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mentse el a XLTM-fájlt a Streambe C++-on keresztül" %}}
A DOCX XLTM-vé konvertálása után az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) lehetővé teszi a dokumentum adatfolyamba való mentését. Fájlok adatfolyamba mentéséhez hozzon létre egy MemoryStream vagy FileStream objektumot, és mentse a fájlt az adatfolyam objektumba az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) meghívásával. az objektum [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) metódusával. Adja meg a kívánt fájlformátumot a [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) felsorolással a [Save](https://reference.aspose.) meghívásakor módszerrel.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-excel/" name="DOCX Nak nek EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xltx/" name="DOCX Nak nek XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-tsv/" name="DOCX Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xlsb/" name="DOCX Nak nek XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xlt/" name="DOCX Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xls/" name="DOCX Nak nek XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-dif/" name="DOCX Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-fods/" name="DOCX Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xltm/" name="DOCX Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xlam/" name="DOCX Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-sxc/" name="DOCX Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xlsx/" name="DOCX Nak nek XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-ods/" name="DOCX Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/docx-to-xlsm/" name="DOCX Nak nek XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}