---
title: Konvertálja a EXCEL-t POTM-be Python segítségével
description: EXCEL-ből POTM-be konvertálás a Python-alkalmazásokban Microsoft Office használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a EXCEL-t POTM-be Python segítségével" h2="EXCEL-ből POTM-be konvertálás a Python-alkalmazásokban a Microsoft Excel<sup>&reg;</sup> vagy a PowerPoint telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Python fejlesztőknek, akik egy EXCEL-t próbálnak hozzáadni a POTM konverziós funkcióhoz az alkalmazáson belül, Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a EXCEL- és POTM-fájlokat.

Főleg két lépésben. Először használja az [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API-t a EXCEL-fájl PDF-be konvertálásához. Ezt követően a PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) használatával mentse a létrehozott PDF-fájlt a kívánt Microsoft PowerPoint formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a EXCEL-t POTM-be konvertálni a Pythonban" %}}
- **1. lépés** Használja a Workbook osztálypéldányt a forrás EXCEL fájl megnyitásához 
- Mentse a EXCEL-fájlt PDF-be a save módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be PDF fájlt a [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) osztály használatával
-  Hívja meg a [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) metódust, miközben megadja a kimeneti POTM fájl elérési útját. Tehát a EXCEL fájl POTM formátumba kerül a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A EXCEL-ből POTM-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) és [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose-cells-python``` és ```pip install aspose.slides```
-  Sőt, Microsoft Windows vagy Linux alapú operációs rendszer (lásd az [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) és [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) bővebben)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="EXCEL mentése PDF-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="PDF mentése POTM-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}