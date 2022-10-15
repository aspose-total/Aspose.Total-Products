---
title: Převést PDF na ICS v Pythonu
description: Ukládejte PDF do ICS v aplikacích Python bez použití Microsoft Word nebo Outlook
url: /cs/python-net/conversion/pdf-to-ics/
family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: ICS
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte PDF na ICS pomocí Pythonu" h2="Převod PDF na ICS ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu PDF na ICS? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to úplný balík různých rozhraní API zabývajících se různými formáty, včetně formátů E-mail, Obrázky a Microsoft Word. Rozhraní API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) a [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), která jsou součástí balíčku [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), usnadňují tento převod pomocí Pythonu. Jedná se o dvoukrokový proces, nejprve načtěte soubor PDF a vykreslete jej do HTML pomocí [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Za druhé načtěte převedený HTML pomocí [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) a uložte jej do formátu ICS.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést PDF na ICS v Pythonu" %}}

- Otevřete zdrojový soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Zavolejte metodu `save`, přičemž jako parametr zadejte cestu k výstupnímu souboru HTML a příslušné možnosti uložení HTML. Váš soubor PDF je tedy převeden na HTML v zadané cestě
- Nyní načtěte uložený soubor HTML pomocí MailMessage.load
- Zavolejte metodu uložení s příslušnou cestou k souboru. Takže nakonec je PDF převeden

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod PDF na ICS je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) a [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Nebo použijte následující příkaz pip ```pip install aspose.words``` a ```pip install Aspose.Email-for-Python-via-NET``` 
- Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/) a [Email](https://docs.aspose.com/email/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů krok za krokem [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit PDF do ICS v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-email/" name="PDF Na EMAIL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-msg/" name="PDF Na MSG" description="" >}},
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-pst/" name="PDF Na PST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-ost/" name="PDF Na OST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-oft/" name="PDF Na OFT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-eml/" name="PDF Na EML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-emlx/" name="PDF Na EMLX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-mbox/" name="PDF Na MBOX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-ics/" name="PDF Na ICS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-net/conversion/pdf-to-vcf/" name="PDF Na VCF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}