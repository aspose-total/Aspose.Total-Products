---
title: Převeďte ODT na XLSM pomocí Pythonu
description: Převod ODT na XLSM ve vašich aplikacích Python bez použití Microsoft Word nebo Excel 

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: XLSM
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést ODT na XLSM pomocí Pythonu" h2="Převod ODT na XLSM ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu ODT na XLSM. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to plný balík různých API zabývajících se různými formáty.

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API pro převod ODT souboru do HTML. Poté pomocí Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) uložte vytvořený HTML do požadovaného formátu Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést ODT na XLSM v Pythonu" %}}
- **Krok 1** Otevřete zdrojový soubor ODT pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Uložte soubor ODT do HTML pomocí metody [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) zadáním názvu souboru a požadované cesty k adresáři
-  **Krok 2** Načtěte soubor HTML s instancí třídy Workbook se souborem a parametry LoadOptions
-  Zavolejte metodu `save` a zadávejte cestu k výstupnímu souboru XLSM. Váš soubor ODT je tedy převeden na XLSM v zadané cestě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod ODT na XLSM je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) a [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Nebo použijte následující příkazy pip ```pip install aspose.words``` a ```pip install aspose-cells-python``` 
-  Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/) a [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle [pokyny krok za krokem](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit ODT do HTML v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit HTML do XLSM v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}