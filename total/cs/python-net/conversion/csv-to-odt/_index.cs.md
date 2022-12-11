---
title: Převeďte CSV na ODT pomocí Pythonu
description: Převod CSV na ODT ve vašich aplikacích Python bez použití Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: CSV
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést CSV na ODT pomocí Pythonu" h2="Převod CSV na ODT ve vašich aplikacích Python bez instalace Microsoft Excel<sup>&reg;</sup> nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu CSV na ODT. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Jedná se o kompletní balíček různých API zabývajících se různými formáty včetně souborů CSV a ODT.

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API pro převod CSV souboru do HTML. Poté pomocí Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) uložte vytvořený HTML do požadovaného formátu Microsoft Word. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést CSV na ODT v Pythonu" %}}
- **Krok 1** Otevřete zdrojový soubor CSV pomocí třídy Workbook
- Uložte soubor CSV do HTML pomocí metody save(file, SaveFormat.HTML) zadáním názvu souboru a požadované cesty k adresáři
-  **Krok 2** Načtěte soubor HTML s instancí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Zavolejte metodu `save` a zadávejte cestu k výstupnímu souboru ODT. Váš soubor CSV je tedy převeden na ODT v zadané cestě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod CSV na ODT je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) a [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Nebo použijte následující příkazy pip ```pip install aspose-cells-python``` a ```pip install aspose.words```
-  Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více pro [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) a [Words](https://docs.aspose.com/words/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle [pokyny krok za krokem](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit CSV do HTML v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit HTML do ODT v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}