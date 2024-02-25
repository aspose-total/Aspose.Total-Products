---
title: Konvertálja a TEXT-t OFT-be Pythonban
description: TEXT mentése OFT formátumba Python alkalmazásokban Microsoft Word vagy Outlook használata nélkül

family: total
platformtag: Python
feature: conversion
informat: TEXT
outformat: OFT
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a TEXT-t OFT-be Python segítségével" h2="TEXT-ből OFT-be konvertálás a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> vagy az Outlook telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára ki próbál TEXT-t hozzáadni OFT-konverziós funkcióhoz az alkalmazáson belül? Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet az átalakítási folyamat automatizálásában. Ez a különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve az e-mailt, a képeket és a Microsoft Word formátumokat. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) csomag részét képező [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) és [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API-k megkönnyítik ezt az átalakítást a Python használatával. Ez egy két lépésből álló folyamat, először töltse be a TEXT fájlt, és az [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) segítségével rendereli HTML-be. Másodszor töltse be a konvertált HTML-t az [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) használatával, és mentse el OFT formátumba.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a TEXT-t OFT-be konvertálni a Pythonban" %}}

- Nyissa meg a forrás TEXT fájlt az [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) osztály használatával
- Hívja meg a "mentés" metódust, miközben paraméterként adja meg a kimeneti HTML fájl elérési útját és a vonatkozó HTML mentési beállításokat. Tehát a TEXT-fájl a megadott elérési úton HTML-be lesz konvertálva
- Most töltse be a mentett HTML-fájlt az MailMessage.load használatával
- Hívja meg a mentési módszert a megfelelő fájl elérési úttal. Tehát végül a TEXT konvertálódik

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A TEXT-ből OFT-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Words](https://pypi.org/project/aspose-words/) és [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Vagy használja a következő pip parancsot: ```pip install aspose.words```` és ```pip install Aspose.Email-for-Python-via-NET``` 
- Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (további információ az [Words](https://docs.aspose.com/words/python-net/system-requirements/) és [Email](https://docs.aspose.com/email/python-net/system-requirements/) esetén), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [INSTALL](https://docs.aspose.com/words/python-net/installation/) lépésről lépésre vonatkozó utasításokat.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TEXT mentése OFT-be Pythonban" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}