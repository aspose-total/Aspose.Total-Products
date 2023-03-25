---
title: Aktualizujte soubor XLSM pomocí Pythonu
description: Upravte dokument XLSM v aplikacích Python bez použití aplikace Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte soubor XLSM přes Python" h2="Upravujte tabulky XLSM prostřednictvím aplikací Python bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře, který se snaží aktualizovat soubory XLSM prostřednictvím aplikace Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API může pomoci automatizovat proces aktualizace. Je to úplný balík různých rozhraní API zabývajících se různými formáty včetně souborů Microsoft Excel. ASPOSE.CELL API, které je součástí balíčku [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), usnadňuje tento proces úpravy. Níže je uveden postup aktualizace dokumentu XLSM.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak aktualizovat soubor XLSM v Pythonu" %}}

- Vytvořte nový objekt třídy [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) se zdrojovým souborem XLSM jako parametrem
- Přístup k příslušnému listu pomocí metody [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Pomocí metody [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) vložte nová data do přístupné buňky
- Uložte soubor jako soubor .xlsm pomocí metody save() předáním souboru s cestou jako parametrem

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na úpravu" %}}

- Pro úpravu XLSM odkazujte na API v rámci projektu přímo z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Nebo použijte následující příkaz pip ```pip install aspose.cells``` 
- Navíc si stáhněte balíček API ze sekce [Stahování](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód - Aktualizujte soubor XLSM v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}