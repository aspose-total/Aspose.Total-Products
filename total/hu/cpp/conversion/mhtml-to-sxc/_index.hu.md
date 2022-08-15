---
title: C++ API a MHTML SXC-vé konvertálásához
description: Konvertálja a MHTML-et SXC-vé a C++ API-n keresztül Microsoft Excel vagy Adobe Reader használata nélkül
url: /hu/cpp/conversion/mhtml-to-sxc/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: SXC
otherformats: TXT MD FODS XLT TSV CSV XLTM DIF XLAM XLSM ODS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderje le a MHTML-et SXC formátumba a C++ alkalmazásokban" h2="MHTML konvertálása SXC-vé a natív C++ alkalmazásokban Microsoft<sup>&reg;</sup> Excel vagy Adobe<sup>&reg;</sup> Acrobat Reader nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
A MHTML konvertálása SXC-vé C++ nyelven az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fájlformátumú automatizálási könyvtárakon keresztül egy egyszerű kétlépéses folyamat. Első lépésben exportálhatja a MHTML-et XLSX-be az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) használatával, majd az [Aspose.Cells for C++] használatával. https://products.aspose.com/cells/cpp/) Spreadsheet Programming API, az XLSX-t SXC-vé konvertálhatja. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API a MHTML SXC-vé konvertálásához" %}}
1. Nyissa meg a MHTML-fájlt a [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztályhivatkozás használatával
2. Konvertálja a MHTML-et XLSX-re a [Mentés](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) tagfüggvény használatával
3. Töltse be az XLSX dokumentumot az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztályhivatkozás használatával
4. Mentse el a dokumentumot SXC formátumba a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) tagfüggvénnyel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Szerezze be vagy állítsa be a MHTML fájlinformációkat a C++ segítségével" %}}
Az [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) emellett lehetővé teszi, hogy információkat szerezzen MHTML-dokumentumáról, és megalapozott döntéseket hozzon az átalakítási folyamat előtt. A MHTML-fájlok fájlspecifikus információinak megtekintéséhez először meg kell hívnia a [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) metódust. [Dokumentum](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) osztály. A DocumentInfo objektum lekérése után megkaphatja az egyes tulajdonságok értékeit. Ezenkívül a tulajdonságokat a DocumentInfo osztály megfelelő metódusaival is beállíthatja.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mentse el a SXC-fájlformátumot a streameléshez C++-on keresztül" %}}
Az [Aspose.Cells for C++](https://products.aspose.com/cells/net/) lehetővé teszi a SXC-fájl formátumú mentését az adatfolyamhoz. Fájlok adatfolyamba mentéséhez hozzon létre egy MemoryStream vagy FileStream objektumot, és mentse a fájlt az adatfolyam objektumba az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) meghívásával. az objektum [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) metódusával. Adja meg a kívánt fájlformátumot a [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) felsorolással a Mentés metódus meghívásakor.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-sxc-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-txt/" name="MHTML Nak nek TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-md/" name="MHTML Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-fods/" name="MHTML Nak nek FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-xlt/" name="MHTML Nak nek XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-tsv/" name="MHTML Nak nek TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-sxc/" name="MHTML Nak nek SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-xltm/" name="MHTML Nak nek XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-dif/" name="MHTML Nak nek DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-xlam/" name="MHTML Nak nek XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-xlsm/" name="MHTML Nak nek XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-ods/" name="MHTML Nak nek ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/cpp/conversion/mhtml-to-xlsb/" name="MHTML Nak nek XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}