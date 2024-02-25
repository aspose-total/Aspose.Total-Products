---
title: Převeďte PDF na MHTML v Pythonu
description: Formát webového archivu PDF na mhtml a převod souborů HtmlFixed ve vašich aplikacích Python bez použití aplikace Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte PDF na MHTML pomocí Pythonu" h2="Převod PDF na MHTML, HtmlFixed a HTML ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat funkci převodu PDF na MHTML (formát webového archivu) nebo HtmlFixed, znamená chtít uložit dokument ve formátu HTML pomocí absolutně umístěných prvků v aplikaci. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to plný balík různých API zabývajících se různými formáty. 

K přidání funkce převodu PDF na MHTML používáme API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), které je součástí balíčku [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/). V případě, že je soubor PDF jednoduchý, pak jsou to jen dva řádky kódu. Načtěte soubor PDF a zavolejte metodu uložení s příslušnou cestou k souboru spolu s výčtem SaveFormat jako MHTML nebo HTML_FIXED. Ale v případě, že je potřeba obnovit model dokumentu co nejblíže původnímu, je potřeba do výsledného dokumentu uložit nějaké extra informace, tzv. round-trip information.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak Převeďte PDF na MHTML v Pythonu" %}}
- Načtěte zdrojový soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Vytvořte instanci [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Nastavte export_roundtrip_information jako True
- Zadejte [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) jako MHTML
- Zavolejte metodu `save`, přičemž jako parametry zadejte cestu k výstupnímu souboru a SaveFormat. Váš soubor PDF je tedy převeden na MHTML na zadané cestě.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}

- Pro převod formátu PDF na MHTML nebo HtmlFixed je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Nebo použijte následující příkazy pip ```pip install aspose.words```
- Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů [INSTALL](https://docs.aspose.com/words/python-net/installation/) krok za krokem.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit PDF do MHTML v Pythonu – jednoduché" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-mhtml-simple.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Převod PDF do MHTML v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-mhtml-conversion-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}