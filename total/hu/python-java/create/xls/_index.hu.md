---
title: XLS létrehozása Pythonban
description: XLS-fájl létrehozása Python-alkalmazásokkal Microsoft Office használata nélkül. 

family: total
platformtag: Python
feature: create
informat: XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Hozzon létre XLS-t Python segítségével" h2="XLS létrehozása Python-alkalmazásaival a Microsoft Office<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy fejlesztő számára ki próbál XLS fájlokat létrehozni Python alkalmazáson keresztül? Az [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API segíthet automatizálni a létrehozási folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a Microsoft Office fájlokat és képeket. Az [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) csomag részét képező [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API megkönnyíti ezt a generálási folyamatot. Az alábbiakban az alkotás folyamata látható. Ezenkívül a fejlesztők egyszerűen javíthatják a XLS-fájl módosítására vonatkozó alkalmazást. A XLS fájl Python használatával történő frissítése ugyanaz, kivéve, hogy a munkafüzet objektum létrehozásakor paraméterként meglévő fájlt igényel.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLS fájl létrehozása Pythonban" %}}

- Hozzon létre új [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) osztályú objektumot FájlFormatType paraméterrel
- Hozzáférés a szükséges [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet)-hez [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) módszerrel
- Szúrjon be adatokat az elért cellába [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) módszerrel
- Mentse el a dokumentumot .xls fájlként [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) használatával úgy, hogy paraméterként adja át az elérési utat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Létrehozási követelmények" %}}

- A XLS generálásához referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Vagy használja a következő pip parancsot: ```pip install aspose.cells``` 
- Ezenkívül töltse le az API-csomagot a [downloads](https://releases.aspose.com/cells/python-java) szakaszból 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS létrehozása Pythonban" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}