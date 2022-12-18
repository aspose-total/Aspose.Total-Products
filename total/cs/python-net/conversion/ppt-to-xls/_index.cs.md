---
title: Převeďte PPT na XLS pomocí Pythonu
description: Převod PPT na XLS ve vašich aplikacích Python bez použití Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPT
outformat: XLS
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést PPT na XLS pomocí Pythonu" h2="Převod PPT na XLS ve vašich aplikacích Python bez instalace Microsoft PowerPoint<sup>&reg;</sup> nebo Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu PPT na XLS. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Jedná se o kompletní balíček různých API zabývajících se různými formáty včetně souborů PPT a XLS.

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API pro převod PPT souboru do HTML. Poté pomocí Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) uložte vytvořený HTML do požadovaného formátu Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést PPT na XLS v Pythonu" %}}
- **Krok 1** Pomocí instance třídy [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) otevřete zdrojový soubor PPT 
- Uložte soubor PPT do HTML pomocí metody [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) zadáním názvu souboru a požadované cesty k adresáři
-  **Krok 2** Načtěte soubor HTML s instancí třídy Workbook
-  Zavolejte metodu `save` a zadávejte cestu k výstupnímu souboru XLS. Váš soubor PPT je tedy převeden na XLS v zadané cestě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod PPT na XLS je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) a [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Nebo použijte následující příkazy pip ```pip install aspose.slides``` a ```pip install aspose-cells-python```
-  Navíc operační systém založený na Microsoft Windows nebo Linux (více viz [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) a [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit PPT do HTML v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit HTML do XLS v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}