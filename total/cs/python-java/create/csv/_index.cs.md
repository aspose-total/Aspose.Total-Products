---
title: Vytvořte CSV v Pythonu
description: Vygenerujte soubor CSV pomocí aplikací Python bez použití sady Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vytvořte CSV pomocí Pythonu" h2="Vytvářejte CSV prostřednictvím aplikací Python bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře, který se snaží vytvářet soubory CSV prostřednictvím aplikace Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API může pomoci automatizovat proces vytváření. Je to úplný balík různých rozhraní API zabývajících se různými formáty, včetně souborů Microsoft Office a obrázků. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API, které je součástí balíčku [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), usnadňuje tento proces generování. Níže je postup tvorby. Kromě toho mohou vývojáři snadno vylepšit aplikaci pro úpravu souboru CSV. Aktualizace souboru CSV pomocí procesu Python je stejná s tím rozdílem, že při vytváření objektu Workbook vyžaduje existující soubor jako parametr.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubor CSV v Pythonu" %}}

- Vytvořte nový objekt třídy [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) s parametrem SouborFormatType
- Získejte přístup k požadovanému [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) pomocí metody [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Vložte data do přístupné buňky pomocí metody [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Uložte dokument jako soubor .csv pomocí [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String) předáním souboru s cestou jako parametrem

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na vytvoření" %}}

- Pro generování CSV odkazujte na API v rámci projektu přímo z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Nebo použijte následující příkaz pip ```pip install aspose.cells``` 
- Navíc si stáhněte balíček API ze sekce [downloads](https://downloads.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Vytvořte CSV v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xls/" name="generovat XLS Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xlsx/" name="Vytvořit XLSX Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/csv/" name="Vytvořit CSV Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xlsb/" name="Vytvořit XLSB Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xlsm/" name="Vytvořit XLSM Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xlt/" name="Vytvořit XLT Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xltx/" name="Vytvořit XLTX Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/xltm/" name="Vytvořit XLTM Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/ods/" name="Vytvořit ODS Soubor" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/python-java/create/tsv/" name="Vytvořit TSV Soubor" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}