---
title: Konvertálja a XLT-et képpé Python segítségével
description: XLT kép TIFF BMP PNG JPEG GIF EMF SVG konverzió a Python-alkalmazásokban Microsoft Excel használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: XLT
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a XLT-et képpé a Python segítségével" h2="XLT-ből JPG, TIFF, BMP, PNG, GIF képek konvertálása a Python-alkalmazásokban a Microsoft Office<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python fejlesztőknek, akik XLT-et próbálnak hozzáadni a PNG, BMP, TIFF, JPEG és GIF képkonverziós funkcióhoz az alkalmazáson belül. Mint néha, az Excel-táblázatok beágyazása szükséges a webes vagy asztali alkalmazásokba. Ilyen esetekben az egyetlen megoldás a táblázatok képekké történő exportálása. Az [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API segíthet az Excel-fájlok képekké exportálásában, valamint az átalakítási folyamat automatizálásában. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a Microsoft Excel formátumokat is, az [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) alárendelt API-n keresztül. Jelenleg a Python Excel to Image Converter API támogatja az Excel-fájlok konvertálását EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM és Office-kompatibilis EMF formátumba, vagy ellenőrizze a támogatott [Formátumok](https://docs.aspose.com/cells/python-java/supported-file-formats/)-t. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a XLT-et képekké konvertálni a Pythonban" %}}

- Hozzon létre [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) osztályú objektumot a XLT fájl betöltéséhez
- Használja a [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) osztályt, és adja meg a kimeneti képre vonatkozó beállításokat
- Hozzáférés a munkalaphoz a konvertáláshoz [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) módszerrel
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Mentse el a munkalap összes oldalát képként a [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) módszerrel. Most a XLT fájlt képekké alakítja a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A XLT-ből képekké (JPG, PNG, GIF, BMP, TIFF) konvertáláshoz referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Vagy használja a következő pip parancsot: ```pip install aspose.cells``` 
- Ezenkívül töltse le az API-csomagot a [Letöltések](https://releases.aspose.com/cells/python-java) szakaszból 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT képek konvertálása Python segítségével" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}