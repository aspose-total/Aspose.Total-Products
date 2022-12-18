---
title: Konvertálja a POTM-t CSV-be Python segítségével
description: POTM-ből CSV-be konvertálás a Python-alkalmazásokban Microsoft Office használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: POTM
outformat: CSV
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a POTM-t CSV-be Python segítségével" h2="POTM-ből CSV-be konvertálás a Python-alkalmazásokban a Microsoft PowerPoint<sup>&reg;</sup> vagy az Excel telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára, aki egy POTM-t próbál hozzáadni a CSV-hez konvertáló funkciót az alkalmazáson belül. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet az átalakítási folyamat automatizálásában. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a POTM- és CSV-fájlokat.

Főleg két lépésben. Először is használja az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API-t a POTM fájl HTML formátumba konvertálásához. Ezután az Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) használatával mentse a létrehozott HTML-t a kívánt Microsoft Excel formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a POTM-t CSV-be konvertálni a Pythonban" %}}
- **1. lépés** Használja a [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) osztálypéldányt a forrás POTM fájl megnyitásához 
- Mentse a POTM fájlt HTML-be a [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be HTML-fájlt a Workbook osztály egy példányával
-  Hívja meg a "mentés" metódust, miközben megadja a kimeneti CSV fájl elérési útját. Tehát a POTM-fájl CSV-re lesz konvertálva a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A POTM-ből CSV-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) és [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose.slides```` és ```pip install aspose-cells-python```
-  Sőt, Microsoft Windows vagy Linux alapú operációs rendszer (lásd az [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) és [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) bővebben)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POTM mentése HTML-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="HTML mentése CSV-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}