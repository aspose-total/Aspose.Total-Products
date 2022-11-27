---
title: Aktualizujte soubory Excel pomocí Pythonu 

description: Upravujte dokumenty Microsoft Excel XLSX, XLS, CSV bez instalace Microsoft Office v rámci aplikací Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte dokumenty Excel pomocí Pythonu" h2="Upravujte soubory Microsoft Excel XLSX, XLS v aplikacích Python bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Je běžné, že organizace aktualizují svá data uložená v excelových souborech, jako jsou data studentů, záznamy pacientů a seznam skladových položek atd. prostřednictvím firemního softwaru. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API poskytuje funkce úpravy tabulek prostřednictvím softwaru. Programátoři mohou vylepšit software pomocí možností úprav integrací API a napsáním několika řádků kódu. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API, které je součástí balíčku [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), usnadňuje tento proces úpravy. Níže je uveden postup aktualizace dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualizujte dokumenty Excel pomocí Pythonu" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API poskytuje třídu Workbook, která zpracovává načítání excelových tabulek. Proces je jednoduchý. Vytvořte objekt třídy [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) poskytnutím zdrojového souboru jako parametru. Použijte metodu [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) pro přístup k příslušnému listu poskytnutím jeho indexu. zavolejte metodu [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) k úpravě obsahu v buňce, ke které se přistupuje, a nakonec vyvolejte metodu save() pro uložení dokumentu.

{{% blocks/products/pf/feature-page-code h3="Python – aktualizace dokumentů aplikace Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizace">}}