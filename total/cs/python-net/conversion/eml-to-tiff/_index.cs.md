---
title: Převést EML na TIFF v Pythonu
description: Uložte EML do TIFF ve svých aplikacích Python bez použití Microsoft Outlook nebo Word 

family: total
platformtag: Python
feature: conversion
informat: EML
outformat: TIFF
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte EML na TIFF pomocí Pythonu" h2="Převod EML na TIFF ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu EML na TIFF? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to úplný balík různých rozhraní API zabývajících se různými formáty, včetně formátů E-mail, Obrázky a Microsoft Word. Rozhraní API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) a [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), která jsou součástí balíčku [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), usnadňují tento převod pomocí Pythonu. Jedná se o dvoukrokový proces, nejprve načtěte e-mail a vykreslete jej do HTML pomocí [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/). Za druhé načtěte převedený HTML pomocí [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) a uložte jej do formátu TIFF.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést EML na TIFF v Pythonu" %}}

- Otevřete zdrojový soubor EML pomocí třídy MailMessage.load
- Zavolejte metodu `save`, přičemž jako parametr zadejte cestu k výstupnímu souboru HTML a příslušné možnosti uložení HTML. Váš soubor EML je tedy převeden na HTML v zadané cestě
- Nyní načtěte uložený soubor HTML pomocí [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Zavolejte metodu uložení s příslušnou cestou k souboru. Takže nakonec je EML převeden

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod EML na TIFF je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) a [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Nebo použijte následující příkaz pip ```pip install aspose.words``` a ```pip install Aspose.Email-for-Python-via-NET``` 
- Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/) a [Email](https://docs.aspose.com/email/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů krok za krokem [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit EML do TIFF v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}