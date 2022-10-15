---
title: Převést PS na MBOX v Pythonu
description: Ukládejte PS do MBOX v aplikacích Python bez použití Microsoft Word nebo Outlook
url: /cs/python-net/conversion/ps-to-mbox/
family: total
platformtag: Python
feature: conversion
informat: PS
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte PS na MBOX pomocí Pythonu" h2="Převod PS na MBOX ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu PS na MBOX? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to úplný balík různých rozhraní API zabývajících se různými formáty, včetně formátů E-mail, Obrázky a Microsoft Word. Rozhraní API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) a [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), která jsou součástí balíčku [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), usnadňují tento převod pomocí Pythonu. Jedná se o dvoukrokový proces, nejprve načtěte soubor PS a vykreslete jej do HTML pomocí [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Za druhé načtěte převedený HTML pomocí [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) a uložte jej do formátu MBOX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést PS na MBOX v Pythonu" %}}

- Otevřete zdrojový soubor PS pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Zavolejte metodu `save`, přičemž jako parametr zadejte cestu k výstupnímu souboru HTML a příslušné možnosti uložení HTML. Váš soubor PS je tedy převeden na HTML v zadané cestě
- Nyní načtěte uložený soubor HTML pomocí MailMessage.load
- Zavolejte metodu uložení s příslušnou cestou k souboru. Takže nakonec je PS převeden

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod PS na MBOX je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) a [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Nebo použijte následující příkaz pip ```pip install aspose.words``` a ```pip install Aspose.Email-for-Python-via-NET``` 
- Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/) a [Email](https://docs.aspose.com/email/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů krok za krokem [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit PS do MBOX v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-email/" name="PS Na EMAIL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-msg/" name="PS Na MSG" description="" >}},
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-pst/" name="PS Na PST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-ost/" name="PS Na OST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-oft/" name="PS Na OFT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-eml/" name="PS Na EML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-emlx/" name="PS Na EMLX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-mbox/" name="PS Na MBOX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-ics/" name="PS Na ICS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/ps-to-vcf/" name="PS Na VCF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}