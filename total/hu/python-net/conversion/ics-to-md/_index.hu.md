---
title: Konvertálja a ICS-t MD-be Pythonban
description: Mentse a ICS-t MD formátumba Python-alkalmazásaiban Microsoft Outlook vagy Word használata nélkül 
url: /hu/python-net/conversion/ics-to-md/
family: total
platformtag: Python
feature: conversion
informat: ICS
outformat: MD
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertálja a ICS-t MD-be Python segítségével" h2="ICS-ből MD-be konvertálás a Python-alkalmazásokban a Microsoft Word<sup>&reg;</sup> vagy az Outlook telepítése nélkül." >}}

{{% blocks/products/pf/feature-page-summary %}}

Egy Python fejlesztő számára ki próbál ICS-t hozzáadni MD-konverziós funkcióhoz az alkalmazáson belül? Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API segíthet automatizálni a konverziós folyamatot. Különféle API-k teljes csomagja, amelyek különböző formátumokkal foglalkoznak, beleértve az e-mailt, a képeket és a Microsoft Word formátumokat. Az [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) csomag részét képező [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) és [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API-k megkönnyítik ezt az átalakítást a Python használatával. Ez egy kétlépcsős folyamat, először töltse be az e-mailt, és jelenítse meg HTML-be az [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)-en keresztül. Másodszor töltse be a konvertált HTML-t az [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) segítségével, és mentse el MD formátumba.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet a ICS-t MD-be konvertálni a Pythonban" %}}

- Nyissa meg a forrás ICS fájlt az MailMessage.load osztály segítségével
- Hívja meg a "mentés" metódust, miközben paraméterként adja meg a kimeneti HTML fájl elérési útját és a vonatkozó HTML mentési beállításokat. Tehát a ICS-fájl a megadott elérési úton HTML-be lesz konvertálva
- Most töltse be a mentett HTML-fájlt az [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) használatával
- Hívja meg a mentési módszert a megfelelő fájl elérési úttal. Tehát végül a ICS konvertálódik

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

- A ICS-ből MD-be konvertáláshoz Python 3.5 vagy újabb verzió szükséges
- Referencia API-k a projekten belül közvetlenül a PyPI-ből ([Aspose.Words](https://pypi.org/project/aspose-words/) és [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Vagy használja a következő pip parancsot: ```pip install aspose.words```` és ```pip install Aspose.Email-for-Python-via-NET``` 
- Ezenkívül a Microsoft Windows vagy Linux alapú operációs rendszer (további információ az [Words](https://docs.aspose.com/words/python-net/system-requirements/) és [Email](https://docs.aspose.com/email/python-net/system-requirements/) esetén), valamint Linux esetén ellenőrizze a gcc és libpython további követelményeit, és kövesse az [INSTALL](https://docs.aspose.com/words/python-net/installation/) lépésről lépésre vonatkozó utasításokat.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ICS mentése MD-be Pythonban" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-doc/" name="ICS Nak nek DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-docm/" name="ICS Nak nek DOCM" description="" >}},
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-docx/" name="ICS Nak nek DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-dot/" name="ICS Nak nek DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-dotm/" name="ICS Nak nek DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-dotx/" name="ICS Nak nek DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-odt/" name="ICS Nak nek ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-ott/" name="ICS Nak nek OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-rtf/" name="ICS Nak nek RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-wordml/" name="ICS Nak nek WORDML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-word/" name="ICS Nak nek Word" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-emf/" name="ICS Nak nek EMF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-epub/" name="ICS Nak nek EPUB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-flatopc/" name="ICS Nak nek FLATOPC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-md/" name="ICS Nak nek MD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-pdf/" name="ICS Nak nek PDF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-ps/" name="ICS Nak nek PS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-text/" name="ICS Nak nek TEXT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-bmp/" name="ICS Nak nek BMP" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-gif/" name="ICS Nak nek GIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-png/" name="ICS Nak nek PNG" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-tiff/" name="ICS Nak nek TIFF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-svg/" name="ICS Nak nek SVG" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-jpeg/" name="ICS Nak nek JPEG" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-xps/" name="ICS Nak nek XPS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/python-net/conversion/ics-to-image/" name="ICS Nak nek IMAGE" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}