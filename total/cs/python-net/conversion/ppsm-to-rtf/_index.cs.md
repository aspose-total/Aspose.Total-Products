---
title: Převést PPSM na RTF v Pythonu
description: Převod PPSM na RTF ve vašich aplikacích Python bez použití Microsoft Word nebo PowerPoint 
url: /cs/python-net/conversion/ppsm-to-rtf/
family: total
platformtag: Python
feature: conversion
informat: PPSM
outformat: RTF
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte PPSM na RTF pomocí Pythonu" h2="Převod PPSM na RTF ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat funkci převodu PPSM na RTF v rámci aplikace? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to plný balík různých API zabývajících se různými formáty. Tak **Jak převést PPSM na RTF v Pythonu?**

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API pro převod PPSM souboru do PDF. Poté pomocí Microsoft Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) uložte vytvořený PDF do Microsoft Wordu ve formátu RTF. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést PPSM na RTF v Pythonu" %}}
-  **Krok 1** Načtěte soubor PDF s instancí třídy [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Volejte metodu `save` a zadávejte cestu k výstupnímu souboru a SaveFormat.PDF jako parametry. Váš soubor PPSM je tedy převeden na PDF v zadané cestě.
- **Krok 2** Otevřete soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Uložte soubor PDF do souboru RTF pomocí metody [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) zadáním názvu souboru a požadované cesty k adresáři.
- Zde je další úryvek kódu pro PowerPoint Presentation to Word (Microsoft Powerpoint to Word)[https://products.aspose.com/total/python-net/conversion/] převod.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod PPSM na RTF je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) a [Aspose.Words](https://pypi.org/project/aspose-words/)) popř.
- Použijte následující příkazy pip ```pip install aspose.slides``` a ```pip install aspose.words```. Navíc,
- Microsoft Windows nebo OS založený na Linuxu (více viz [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) a [Words](https://docs.aspose.com/words/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů krok za krokem [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit PPSM do PDF v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit PDF do RTF v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}