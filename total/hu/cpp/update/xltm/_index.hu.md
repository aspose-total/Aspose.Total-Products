---
title: Frissítse a XLTM fájlt C++ használatával
description: Módosítsa a XLTM-dokumentumot C++ alkalmazásokban Microsoft Excel használata nélkül.
family: total
platformtag: C++
feature: update
informat: XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Frissítse a XLTM fájlt C++ segítségével" h2="Módosítsa a XLTM-táblázatokat C++ alapú alkalmazásaival a Microsoft Office<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Programozónak, aki C++ alkalmazáson belül próbálja frissíteni a XLTM fájlokat, Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API segíthet automatizálni a frissítési folyamatot. Különféle C++ könyvtárak teljes csomagja, amelyek többféle formátummal foglalkoznak, beleértve a Microsoft Excel dokumentumokat is. Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomag részét képező [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API megkönnyíti ezt a módosítási folyamatot. A XLTM-dokumentum frissítésének folyamata egyszerű: először eléri a lapot, majd frissíti a cellaértéket Excelben a C++ használatával.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLTM fájl frissítése C++ nyelven" %}}

- Töltse be a XLTM fájlt a [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) használatával
- A releváns [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) elérése GetIWorksheets()->GetObjectByIndex(0) használatával és a releváns cella a GetICells()->GetObjectByIndex használatával
- Szúrjon be új adatokat az elért cellába PutValue módszerrel
- Mentse el a fájlt .xltm fájlként a Mentés metódussal úgy, hogy paraméterként adja meg az elérési utat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Módosítási követelmények" %}}

- A XLTM módosításához kövesse a [rendszerkövetelmények](https://docs.aspose.com/cells/cpp/system-requirements/)-ot Windows és Linux rendszerekhez 
- Telepítés parancssorból ```nuget install Aspose.Total.Cpp``` néven
- Vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` segítségével
- Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [Letöltések](https://releases.aspose.com/cells/cpp)-től

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód - Frissítse a XLTM fájlt C++ nyelven" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}