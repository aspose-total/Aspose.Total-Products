---
title: Frissítse a XLSM fájlt Python használatával
description: Módosítsa a XLSM-dokumentumot Python-alkalmazásokban Microsoft Excel használata nélkül. 

family: total
platformtag: Python
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Frissítse a XLSM fájlt Python segítségével" h2="Módosítsa a XLSM-táblázatokat Python-alkalmazásain keresztül a Microsoft Office<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy fejlesztő számára ki próbálja meg frissíteni a XLSM fájlokat Python alkalmazáson keresztül? Az [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API segíthet automatizálni a frissítési folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a Microsoft Excel fájlokat is. Az [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) csomag részét képező ASPOSE.CELL API megkönnyíti ezt a módosítási folyamatot. Az alábbiakban a XLSM-dokumentum frissítésének folyamata látható.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="A XLSM fájl frissítése a Pythonban" %}}

- Hozzon létre új [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) osztályú objektumot, amelynek paramétere a forrás XLSM fájl
- A vonatkozó munkalap elérése [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) módszerrel
- Szúrjon be új adatokat az elért cellába [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) módszerrel
- Mentse el a fájlt .xlsm fájlként a save() metódussal úgy, hogy paraméterként adja meg az elérési utat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Módosítási követelmények" %}}

- A XLSM módosításához hivatkozzon a projekten belüli API-kra közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Vagy használja a következő pip parancsot: ```pip install aspose.cells``` 
- Ezenkívül töltse le az API-csomagot a [Letöltések](https://releases.aspose.com/cells/python-java) szakaszból

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód - Frissítse a XLSM fájlt Pythonban" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}