---
title: Konvertálja a XLS-t RTF-be Python segítségével
description: XLS-ből RTF-be konvertálás a Python-alkalmazásokban Microsoft Office használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: XLS
outformat: RTF
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a XLS-t RTF-be Python segítségével" h2="XLS-ből RTF-be konvertálás a Python-alkalmazásokban a Microsoft Excel<sup>&reg;</sup> vagy a Word telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára, aki egy XLS-t próbál hozzáadni a RTF-hez konvertáló funkciót az alkalmazáson belül. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve a XLS- és RTF-fájlokat.

Főleg két lépésben. Először is használja az [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API-t a XLS fájl HTML formátumba konvertálásához. Ezután a Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) használatával mentse a létrehozott HTML-t a kívánt Microsoft Word formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a XLS-t RTF-be konvertálni a Pythonban" %}}
- **1. lépés** Nyissa meg a forrás XLS fájlt a Workbook osztály használatával
- Mentse a XLS-fájlt HTML-be a save(file, SaveFormat.HTML) módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be HTML-fájlt a [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály egy példányával
-  Hívja meg a "mentés" metódust, miközben megadja a kimeneti RTF fájl elérési útját. Tehát a XLS fájl RTF formátumba kerül a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A XLS-ből RTF-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) és [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose-cells-python``` és ```pip install aspose.words```
-  Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (lásd bővebben az [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) és [Words](https://docs.aspose.com/words/python-net/system-requirements/)), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [lépésről lépésre utasításokat](https://docs.aspose.com/words/python-net/installation/) parancsot.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS mentése HTML-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="HTML mentése RTF-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter XLS-hez RTF-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-word/" name="XLS Nak nek WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-doc/" name="XLS Nak nek DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-docx/" name="XLS Nak nek DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-docm/" name="XLS Nak nek DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-dot/" name="XLS Nak nek DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-dotm/" name="XLS Nak nek DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-dotx/" name="XLS Nak nek DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-mobi/" name="XLS Nak nek MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-odt/" name="XLS Nak nek ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-ott/" name="XLS Nak nek OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-rtf/" name="XLS Nak nek RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/xls-to-wordml/" name="XLS Nak nek WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}