---
title: Konvertálja a DOT-t SXC-be Python segítségével
description: DOT-ből SXC-be konvertálás a Python-alkalmazásokban Microsoft Word vagy Excel használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: DOT
outformat: SXC
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a DOT-t SXC-be Python segítségével" h2="DOT-ből SXC-be konvertálás a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> vagy az Excel telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára, aki egy DOT-t próbál hozzáadni a SXC-hez konvertáló funkciót az alkalmazáson belül. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak.

Főleg két lépésben. Először is használja az [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API-t a DOT fájl HTML formátumba konvertálásához. Ezután az Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) használatával mentse a létrehozott HTML-t a kívánt Microsoft Excel formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a DOT-t SXC-be konvertálni a Pythonban" %}}
- **1. lépés** Nyissa meg a forrás DOT fájlt a [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály használatával
- Mentse a DOT-fájlt HTML-be a [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be HTML-fájlt a Workbook osztály egy példányával, fájllal és LoadOptions paraméterekkel
-  Hívja meg a "mentés" metódust, miközben megadja a kimeneti SXC fájl elérési útját. Tehát a DOT-fájl SXC-re lesz konvertálva a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A DOT-ből SXC-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Words](https://pypi.org/project/aspose-words/) és [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose.words``` és ```pip install aspose-cells-python``` 
-  Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (lásd bővebben az [Words](https://docs.aspose.com/words/python-net/system-requirements/) és [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [lépésről lépésre utasításokat](https://docs.aspose.com/words/python-net/installation/) parancsot.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DOT mentése HTML-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="HTML mentése SXC-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-excel/" name="DOT Nak nek EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xls/" name="DOT Nak nek XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xlsx/" name="DOT Nak nek XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-csv/" name="DOT Nak nek CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-dif/" name="DOT Nak nek DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-fods/" name="DOT Nak nek FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-ods/" name="DOT Nak nek ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-sxc/" name="DOT Nak nek SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-tsv/" name="DOT Nak nek TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xlam/" name="DOT Nak nek XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xlsb/" name="DOT Nak nek XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xlt/" name="DOT Nak nek XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xltm/" name="DOT Nak nek XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xltx/" name="DOT Nak nek XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-xlsm/" name="DOT Nak nek XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}