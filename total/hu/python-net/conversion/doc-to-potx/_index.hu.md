---
title: Konvertálja a DOC-t POTX-be Pythonban
description: DOC-ből POTX-be konvertálás a Python-alkalmazásokban Microsoft Word vagy PowerPoint használata nélkül 
url: /hu/python-net/conversion/doc-to-potx/
family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: POTX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a DOC-t POTX-be Python segítségével" h2="DOC-ből POTX-be konvertálás a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> vagy a PowerPoint telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára, aki DOC-t próbál hozzáadni POTX-konverziós funkcióhoz az alkalmazáson belül? Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak. Így **Hogyan lehet a DOC-t POTX-be konvertálni a Pythonban?**

Főleg két lépésben. Először használja az [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API-t a DOC-fájl PDF-be konvertálásához. Ezt követően a PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) használatával mentse a létrehozott PDF-fájlt a Prezentációba POTX formátumban. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a DOC-t POTX-be Pythonban" %}}
- **1. lépés** Nyissa meg a forrás DOC fájlt az [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály használatával
- Mentse el a DOC-fájlt PDF-be az [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával.
-  **2. lépés** Töltse be az [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) osztály példányát tartalmazó PDF-fájlt
-  Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.POTX fájlt. Tehát a DOC fájl POTX formátumba kerül a megadott elérési úton.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A DOC-ből POTX-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) és [Aspose.Words](https://pypi.org/project/aspose-words/)) vagy
- Használja a következő pip parancsokat: ```pip install aspose.slides```` és ```pip install aspose.words```. Ráadásul,
- Microsoft Windows vagy Linux alapú operációs rendszer (lásd bővebben az [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) és [Words](https://docs.aspose.com/words/python-net/system-requirements/)), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse lépésről lépésre az [INSTALL](https://docs.aspose.com/words/python-net/installation/) utasításokat.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DOC mentése PDF-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="PDF mentése POTX-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}