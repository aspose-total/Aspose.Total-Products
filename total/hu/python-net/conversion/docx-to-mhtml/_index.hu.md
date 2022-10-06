---
title: DOCX konvertálása MHTML-re Pythonban
description: DOCX-ből mhtml webarchívum-formátumba és HTML-fix fájlkonverzió a Python-alkalmazásokban Microsoft Word használata nélkül 
url: /hu/python-net/conversion/docx-to-mhtml/
family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a DOCX-t MHTML-re Python segítségével" h2="DOCX-ből MHTML-vé, HtmlFixed és HTML-konverzió a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Az a Python fejlesztő, aki egy DOCX-t próbál hozzáadni az MHTML-hez (webarchívum formátum) konverziós szolgáltatáshoz vagy HtmlFixed eszközhöz, szeretné a dokumentumot HTML formátumban menteni, az alkalmazáson belüli abszolút elhelyezett elemek használatával. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet az átalakítási folyamat automatizálásában. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak. 

Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) csomag részét képező [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API-t használjuk a DOCX és MHTML konverziós szolgáltatás hozzáadásához. Abban az esetben, ha a DOCX fájl egyszerű, akkor csak két sornyi kódot tartalmaz. Töltse be a DOCX-fájlt, és hívja meg a mentési metódust a megfelelő fájl elérési úttal a SaveFormat felsorolásával együtt MHTML vagy HTML_FIXED formátumban. De abban az esetben, ha a dokumentummodellt az eredetihez legközelebb kell visszaállítani, akkor el kell menteni néhány extra információt az eredményül kapott dokumentumban, az úgynevezett oda-vissza információ.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan kell DOCX konvertálása MHTML-re Pythonban" %}}
- A forrás DOCX fájl betöltése az [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály használatával
- Hozza létre az [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) példányát.
- Állítsa be az export_roundtrip_information értéket True értékre
- Adja meg az [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/)-ot MHTML-ként
- Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat-ot. Tehát a DOCX-fájl a megadott elérési úton MHTML-re lesz konvertálva.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A DOCX-ből MHTML vagy HtmlFixed formátumba konvertálásához Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Vagy használja a következő pip parancsokat: ```pip install aspose.words```
- Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (lásd még az [Words](https://docs.aspose.com/words/python-net/system-requirements/)-nál) és Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [INSTALL](https://docs.aspose.com/words/python-net/installation/) lépésről lépésre vonatkozó utasításait.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DOCX mentése MHTML-be Pythonban - Egyszerű" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="DOCX konvertálás MHTML-be Pythonban" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/word-to-mhtml/" name="WORD Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/doc-to-mhtml/" name="DOC Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dot-to-mhtml/" name="DOT Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/docx-to-mhtml/" name="DOCX Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/docm-to-mhtml/" name="DOCM Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dotx-to-mhtml/" name="DOTX Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/dotm-to-mhtml/" name="DOTM Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/rtf-to-mhtml/" name="RTF Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/wordml-to-mhtml/" name="WORDML Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/odt-to-mhtml/" name="ODT Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ott-to-mhtml/" name="OTT Nak nek MHTML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/pdf-to-mhtml/" name="PDF Nak nek MHTML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}