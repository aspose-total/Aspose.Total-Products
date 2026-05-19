---
title: PDF konvertálása MHTML-re Pythonban
description: PDF-ből mhtml webarchívum-formátumba és HTML-fix fájlkonverzió a Python-alkalmazásokban Microsoft Word használata nélkül 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a PDF-t MHTML-re Python segítségével" h2="PDF-ből MHTML-vé, HtmlFixed és HTML-konverzió a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Az a Python fejlesztő, aki egy PDF-t próbál hozzáadni az MHTML-hez (webarchívum formátum) konverziós szolgáltatáshoz vagy HtmlFixed eszközhöz, szeretné a dokumentumot HTML formátumban menteni, az alkalmazáson belüli abszolút elhelyezett elemek használatával. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet az átalakítási folyamat automatizálásában. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak. 

Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) csomag részét képező [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API-t használjuk a PDF és MHTML konverziós szolgáltatás hozzáadásához. Abban az esetben, ha a PDF fájl egyszerű, akkor csak két sornyi kódot tartalmaz. Töltse be a PDF-fájlt, és hívja meg a mentési metódust a megfelelő fájl elérési úttal a SaveFormat felsorolásával együtt MHTML vagy HTML_FIXED formátumban. De abban az esetben, ha a dokumentummodellt az eredetihez legközelebb kell visszaállítani, akkor el kell menteni néhány extra információt az eredményül kapott dokumentumban, az úgynevezett oda-vissza információ.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan kell PDF konvertálása MHTML-re Pythonban" %}}
- A forrás PDF fájl betöltése az [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály használatával
- Hozza létre az [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) példányát.
- Állítsa be az export_roundtrip_information értéket True értékre
- Adja meg az [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/)-ot MHTML-ként
- Hívja meg a "save" metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat-ot. Tehát a PDF-fájl a megadott elérési úton MHTML-re lesz konvertálva.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A PDF-ből MHTML vagy HtmlFixed formátumba konvertálásához Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Vagy használja a következő pip parancsokat: ```pip install aspose.words```
- Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (lásd még az [Words](https://docs.aspose.com/words/python-net/system-requirements/)-nál) és Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [INSTALL](https://docs.aspose.com/words/python-net/installation/) lépésről lépésre vonatkozó utasításait.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PDF mentése MHTML-be Pythonban - Egyszerű" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-mhtml-simple.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="PDF konvertálás MHTML-be Pythonban" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-mhtml-conversion-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

PDF‑MHTML átalakítás Python API‑kkal segít a dokumentumtartalom átalakításában egy olyan webarchívum formátumba, amely egyetlen fájlba egyesíti a jelölőnyelvet és a beágyazott erőforrásokat. Ez megkönnyíti a PDF‑információk megőrzését, megjelenítését vagy terjesztését böngészőkompatibilis környezetekben.

Az automatizálás növeli ennek az átalakításnak az értékét azzal, hogy lehetővé teszi a statikus dokumentumokból skálázható módon hordozható, webre kész fájlok előállítását. Támogatja a tartalomkiadást, archiválást, valamint az olyan rendszerek integrációját, amelyek önálló webdokumentum‑kimeneteket igényelnek.

{{% blocks/products/pf/agp/feature-section-col title="Fő felhasználási esetek" %}}

* **Webarchívum létrehozása**  
  PDF‑fájlok átalakítása MHTML‑formátumba böngészőalapú tárolásra és megtekintésre.

* **Hordozható dokumentumkiadás**  
  A dokumentumtartalom megosztása egy önálló, webbarát formátumban.

* **Tartalommegőrzés**  
  A vizuális és szöveges információk megőrzése egy olyan archívumban, amely a webes munkafolyamatokhoz illeszkedik.

* **Rendszerinteroperabilitás**  
  MHTML‑kimenet használata olyan esetekben, amikor a dokumentumcsere a böngészőkompatibilis szabványokkal kell, hogy összhangban legyen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automatizálási forgatókönyvek" %}}

* **Automatizált webes konverziós csővezetékek**  
  Python‑szkriptek PDF‑fájlokat MHTML‑fájlokká alakíthatnak digitális kiadási rendszerek számára.

* **Archiválási terjesztési munkafolyamatok**  
  Az átalakított kimeneteket olyan tárolókba lehet szállítani, amelyek a webarchívum tartalmát kezelik.

* **Kötegelt dokumentumkiadás**  
  Nagy mennyiségű PDF‑fájl átalakítható hordozható webfájlokká manuális beavatkozás nélkül.

* **Dinamikus tartalomexportálás**  
  A rendszerek igény szerint MHTML‑verziókat generálhatnak a dokumentumokról megosztás vagy felülvizsgálat céljából.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}