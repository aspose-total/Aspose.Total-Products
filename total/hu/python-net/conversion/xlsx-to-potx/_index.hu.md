---
title: Konvertálja a XLSX-t POTX-be Python segítségével
description: XLSX-ből POTX-be konvertálás a Python-alkalmazásokban Microsoft Office használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: POTX
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a XLSX-t POTX-be Python segítségével" h2="XLSX-ből POTX-be konvertálás a Python-alkalmazásokban a Microsoft Excel<sup>&reg;</sup> vagy a PowerPoint telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Python fejlesztőknek, akik egy XLSX-t próbálnak hozzáadni a POTX konverziós funkcióhoz az alkalmazáson belül, Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a XLSX- és POTX-fájlokat.

Főleg két lépésben. Először használja az [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API-t a XLSX-fájl PDF-be konvertálásához. Ezt követően a PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) használatával mentse a létrehozott PDF-fájlt a kívánt Microsoft PowerPoint formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a XLSX-t POTX-be konvertálni a Pythonban" %}}
- **1. lépés** Használja a Workbook osztálypéldányt a forrás XLSX fájl megnyitásához 
- Mentse a XLSX-fájlt PDF-be a save módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be PDF fájlt a [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) osztály használatával
-  Hívja meg a [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) metódust, miközben megadja a kimeneti POTX fájl elérési útját. Tehát a XLSX fájl POTX formátumba kerül a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A XLSX-ből POTX-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) és [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose-cells-python``` és ```pip install aspose.slides```
-  Sőt, Microsoft Windows vagy Linux alapú operációs rendszer (lásd az [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) és [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) bővebben)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX mentése PDF-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="PDF mentése POTX-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}