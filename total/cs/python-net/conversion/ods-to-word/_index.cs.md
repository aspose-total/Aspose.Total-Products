---
title: Převeďte ODS na WORD pomocí Pythonu nebo pomocí bezplatného online převodníku
description: Převod ODS na WORD ve vašich aplikacích Python bez použití Microsoft Office nebo online. Před integrací kódu rychle otestujte bezplatný online převodník CSV na POT. 

family: total
platformtag: Python
feature: conversion
informat: ODS
outformat: WORD
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést ODS na WORD pomocí Pythonu nebo online aplikace" h2="Převod ODS na WORD ve vašich aplikacích Python bez instalace Microsoft Excel<sup>&reg;</sup> nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu ODS na WORD. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Jedná se o kompletní balíček různých API zabývajících se různými formáty včetně souborů ODS a WORD.

Je to hlavně ve dvou krocích. Nejprve použijte [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API pro převod ODS souboru do HTML. Poté pomocí Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) uložte vytvořený HTML do požadovaného formátu Microsoft Word. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést ODS na WORD v Pythonu" %}}
- **Krok 1** Otevřete zdrojový soubor ODS pomocí třídy Workbook
- Uložte soubor ODS do HTML pomocí metody save(file, SaveFormat.HTML) zadáním názvu souboru a požadované cesty k adresáři
-  **Krok 2** Načtěte soubor HTML s instancí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Zavolejte metodu `save` a zadávejte cestu k výstupnímu souboru WORD. Váš soubor ODS je tedy převeden na WORD v zadané cestě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod ODS na WORD je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) a [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Nebo použijte následující příkazy pip ```pip install aspose-cells-python``` a ```pip install aspose.words```
-  Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více pro [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) a [Words](https://docs.aspose.com/words/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle [pokyny krok za krokem](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit ODS do HTML v Pythonu - Krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Uložit HTML do WORD v Pythonu - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Zdarma online převodník ODS na WORD</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=ods" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}