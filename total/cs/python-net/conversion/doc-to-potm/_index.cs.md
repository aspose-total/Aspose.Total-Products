---
title: Převést DOC na POTM v Pythonu
description: Převod DOC na POTM ve vašich aplikacích Python bez použití Microsoft Word nebo PowerPoint 
url: /cs/python-net/conversion/doc-to-potm/
family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: POTM
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte DOC na POTM pomocí Pythonu" h2="Převod DOC na POTM ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat funkci převodu DOC na POTM v rámci aplikace? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to plný balík různých API zabývajících se různými formáty. Tak **Jak převést DOC na POTM v Pythonu?**

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API pro převod DOC souboru do PDF. Poté pomocí PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) uložte vytvořený PDF do Presentation jako formát POTM. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést DOC na POTM v Pythonu" %}}
- **Krok 1** Otevřete zdrojový soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Uložte soubor DOC do PDF pomocí metody [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) zadáním názvu souboru a požadované cesty k adresáři.
-  **Krok 2** Načtěte soubor PDF s instancí třídy [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Volejte metodu `save` a zadávejte cestu k výstupnímu souboru a SaveFormat.POTM jako parametry. Váš soubor DOC je tedy převeden na POTM v zadané cestě.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}

- Pro převod DOC na POTM je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) a [Aspose.Words](https://pypi.org/project/aspose-words/)) popř.
- Použijte následující příkazy pip ```pip install aspose.slides``` a ```pip install aspose.words```. Navíc,
- Microsoft Windows nebo OS založený na Linuxu (více viz [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) a [Words](https://docs.aspose.com/words/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů krok za krokem [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit DOC do PDF v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit PDF do POTM v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}