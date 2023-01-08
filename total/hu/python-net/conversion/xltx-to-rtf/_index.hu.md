---
title: Konvertálja a XLTX-t RTF-be Python segítségével
description: XLTX-ből RTF-be konvertálás a Python-alkalmazásokban Microsoft Office használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: XLTX
outformat: RTF
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a XLTX-t RTF-be Python segítségével" h2="XLTX-ből RTF-be konvertálás a Python-alkalmazásokban a Microsoft Excel<sup>&reg;</sup> vagy a Word telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára, aki egy XLTX-t próbál hozzáadni a RTF-hez konvertáló funkciót az alkalmazáson belül. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a XLTX- és RTF-fájlokat.

Főleg két lépésben. Először is használja az [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API-t a XLTX fájl HTML formátumba konvertálásához. Ezután a Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) használatával mentse a létrehozott HTML-t a kívánt Microsoft Word formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a XLTX-t RTF-be konvertálni a Pythonban" %}}
- **1. lépés** Nyissa meg a forrás XLTX fájlt a Workbook osztály használatával
- Mentse a XLTX-fájlt HTML-be a save(file, SaveFormat.HTML) módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be HTML-fájlt a [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály egy példányával
-  Hívja meg a "mentés" metódust, miközben megadja a kimeneti RTF fájl elérési útját. Tehát a XLTX fájl RTF formátumba kerül a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A XLTX-ből RTF-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) és [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose-cells-python``` és ```pip install aspose.words```
-  Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (lásd bővebben az [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) és [Words](https://docs.aspose.com/words/python-net/system-requirements/)), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [lépésről lépésre utasításokat](https://docs.aspose.com/words/python-net/installation/) parancsot.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTX mentése HTML-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="HTML mentése RTF-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-word/" name="XLTX Nak nek WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-doc/" name="XLTX Nak nek DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-docx/" name="XLTX Nak nek DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-docm/" name="XLTX Nak nek DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-dot/" name="XLTX Nak nek DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-dotm/" name="XLTX Nak nek DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-dotx/" name="XLTX Nak nek DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-mobi/" name="XLTX Nak nek MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-odt/" name="XLTX Nak nek ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-ott/" name="XLTX Nak nek OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-rtf/" name="XLTX Nak nek RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xltx-to-wordml/" name="XLTX Nak nek WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}