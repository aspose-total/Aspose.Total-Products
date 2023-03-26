---
title: Konvertálja a JSON formátumot OTP-re C++ segítségével
description: Elemezze a JSON-t OTP-re C++-ban Microsoft PowerPoint használata nélkül

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: OTP
otherformats: PPSX PPS POTM PPT POT PPTM ODP POTX PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a JSON formátumot OTP-re C++ segítségével" h2="C++ API a JSON elemzéséhez OTP-be a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépésben konvertálhatja a JSON-t OTP-vé bármely C++ alkalmazáson belül. Először is, az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) használatával elemezheti a JSON-t PPTX-re. Ezt követően az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) használatával konvertálhatja a PPTX-t OTP-vé. Mindkét API az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomagban található. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot OTP-re C++ segítségével" %}}
1. Hozzon létre egy új [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Mentse el a JSON fájlt PPTX formátumban a [Mentés](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) módszerrel
3. Töltse be a PPTX dokumentumot a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztály használatával
4. Mentse a dokumentumot OTP formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paraméterrel.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és konvertálja a JSON-formátumot OTP-re a C++ segítségével" %}}
A JSON OTP-re történő elemzése közben a sorok és oszlopok méretét is beállíthatja az [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztály JSON-jának betöltésével. Ha ugyanazt a sormagasságot kell beállítania a munkalap minden sorához, ezt a [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a673f16a673f) segítségével teheti meg. ) módszere az [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) gyűjteményben. Hasonlóképpen, ha a munkalap minden oszlopához azonos oszlopszélességet szeretne beállítani, használja az ICells gyűjtemény [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b7)500094b7 metódusát.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON formátumot OTP-vé vízjellel a C++ nyelven" %}}
Az API használatával a JSON-t vízjellel OTP-vé is konvertálhatja. Ha vízjelet szeretne hozzáadni az OTP-dokumentumhoz, először elemezze a JSON-t PPTX-be, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltse be az újonnan létrehozott PPTX fájlt a [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) osztály segítségével, szerezze be az első diát, Add an an Téglalap típusú AutoShape, szövegkeret hozzáadása a téglalaphoz, bekezdés objektum létrehozása szövegkerethez, részobjektum létrehozása bekezdéshez, vízjel hozzáadása a set_Text() segítségével, és elmentheti a dokumentumot az OTP-be.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}