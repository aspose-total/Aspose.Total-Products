---
title: Převeďte XLTM na PPSM pomocí Pythonu
description: Převod XLTM na PPSM ve vašich aplikacích Python bez použití Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLTM
outformat: PPSM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XLTM na PPSM pomocí Pythonu" h2="Převod XLTM na PPSM ve vašich aplikacích Python bez instalace Microsoft Excel<sup>&reg;</sup> nebo PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu XLTM na PPSM, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Jedná se o kompletní balíček různých API zabývajících se různými formáty včetně souborů XLTM a PPSM.

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API pro převod XLTM souboru do PDF. Poté pomocí PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) uložte vytvořený PDF do požadovaného formátu Microsoft PowerPoint. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést XLTM na PPSM v Pythonu" %}}
- **Krok 1** Pomocí instance třídy Workbook otevřete zdrojový soubor XLTM 
- Uložte soubor XLTM do PDF pomocí metody save zadáním názvu souboru a požadované cesty k adresáři
-  **Krok 2** Načtěte soubor PDF pomocí třídy [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Zavolejte metodu [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) a zároveň zadejte cestu k výstupnímu souboru PPSM. Váš soubor XLTM je tedy převeden na PPSM v zadané cestě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}

- Pro převod XLTM na PPSM je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) a [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Nebo použijte následující příkazy pip ```pip install aspose-cells-python``` a ```pip install aspose.slides```
-  Navíc operační systém založený na Microsoft Windows nebo Linux (více viz [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) a [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit XLTM do PDF v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit PDF do PPSM v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}