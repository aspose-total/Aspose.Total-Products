---
title: Konvertálja a DOC-t XLTM-be Python segítségével
description: DOC-ből XLTM-be konvertálás a Python-alkalmazásokban Microsoft Word vagy Excel használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: XLTM
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a DOC-t XLTM-be Python segítségével" h2="DOC-ből XLTM-be konvertálás a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> vagy az Excel telepítése nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára, aki egy DOC-t próbál hozzáadni a XLTM-hez konvertáló funkciót az alkalmazáson belül. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak.

Főleg két lépésben. Először is használja az [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API-t a DOC fájl HTML formátumba konvertálásához. Ezután az Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) használatával mentse a létrehozott HTML-t a kívánt Microsoft Excel formátumba. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a DOC-t XLTM-be konvertálni a Pythonban" %}}
- **1. lépés** Nyissa meg a forrás DOC fájlt a [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály használatával
- Mentse a DOC-fájlt HTML-be a [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) módszerrel a fájlnév és a kívánt könyvtár elérési út megadásával
-  **2. lépés** Töltsön be HTML-fájlt a Workbook osztály egy példányával, fájllal és LoadOptions paraméterekkel
-  Hívja meg a "mentés" metódust, miközben megadja a kimeneti XLTM fájl elérési útját. Tehát a DOC-fájl XLTM-re lesz konvertálva a megadott elérési úton

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A DOC-ből XLTM-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Words](https://pypi.org/project/aspose-words/) és [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Vagy használja a következő pip parancsokat: ```pip install aspose.words``` és ```pip install aspose-cells-python``` 
-  Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (lásd bővebben az [Words](https://docs.aspose.com/words/python-net/system-requirements/) és [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [lépésről lépésre utasításokat](https://docs.aspose.com/words/python-net/installation/) parancsot.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DOC mentése HTML-be Pythonban – 1. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="HTML mentése XLTM-be Pythonban – 2. lépés" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-excel/" name="DOC Nak nek EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xls/" name="DOC Nak nek XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xlsx/" name="DOC Nak nek XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-csv/" name="DOC Nak nek CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-dif/" name="DOC Nak nek DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-fods/" name="DOC Nak nek FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-ods/" name="DOC Nak nek ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-sxc/" name="DOC Nak nek SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-tsv/" name="DOC Nak nek TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xlam/" name="DOC Nak nek XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xlsb/" name="DOC Nak nek XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xlt/" name="DOC Nak nek XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xltm/" name="DOC Nak nek XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xltx/" name="DOC Nak nek XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-xlsm/" name="DOC Nak nek XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}