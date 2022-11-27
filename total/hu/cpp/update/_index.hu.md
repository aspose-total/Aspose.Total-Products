---
title: Frissítse az Excel fájlokat C++ használatával 

description: Microsoft Excel XLSX, XLS, CSV dokumentumok szerkesztése a Microsoft Office C++ alapú alkalmazásokkal történő telepítése nélkül.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Frissítse az Excel dokumentumokat C++ segítségével" h2="Módosítsa a Microsoft Excel XLSX, XLS fájlokat C++ alapú alkalmazásokban a Microsoft Office<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}
Gyakori, hogy a szervezetek céges szoftveren keresztül frissítik az Excel-fájlokban tárolt adataikat, például hallgatói adatok, betegnyilvántartások és raktári cikkek listája stb. Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API biztosítja a táblázatok szoftver segítségével történő módosításának funkcióját. A programozók csak néhány sor API kód írásával bővíthetik a szoftvert a módosítási lehetőségekkel. Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) csomag részét képező [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API megkönnyíti ezt a módosítási folyamatot. Az alábbiakban a Excel-dokumentum frissítésének folyamata látható.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Frissítse az Excel dokumentumokat C++ használatával" %}}

Az [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API használatával töltse be a forrásdokumentumot a [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) használatával. Hozzáférés a [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)-hez a GetIWorksheets()->GetObjectByIndex(0) használatával és a szükséges cellához a GetICells()->GetObjectByIndex használatával. A PutValue módszerrel módosítsa az elért cella tartalmát. Végül hívja meg a save() metódust a dokumentum mentéséhez.

{{% blocks/products/pf/feature-page-code h3="C++ kód – Excel-dokumentumok frissítése" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Frissítés">}}