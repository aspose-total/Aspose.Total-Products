---
title: Převeďte XLTM na obrázek pomocí Pythonu
description: Převod XLTM na obrázek TIFF BMP PNG JPEG GIF EMF SVG ve vašich aplikacích Python bez použití aplikace Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLTM
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XLTM na obrázek přes Python" h2="Převod obrázků XLTM na JPG, TIFF, BMP, PNG, GIF ve vašich aplikacích Python bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat funkci konverze obrázků XLTM do PNG, BMP, TIFF, JPEG a GIF v rámci aplikace. Jako někdy je nutné vložit tabulky Excelu do webových nebo desktopových aplikací. V takových případech je jediným řešením export tabulek do obrázků. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API může pomoci exportovat soubory Excel do obrázků a také automatizovat proces převodu. Je to úplný balík různých rozhraní API zabývajících se různými formáty včetně formátů Microsoft Excel prostřednictvím svého podřízeného API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/). V současné době Python Excel to Image Converter API podporuje převod souborů Excel do EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM a EMF kompatibilní s Office nebo zkontrolujte podporované [Formáty](https://docs.aspose.com/cells/python-java/supported-file-formats/). 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést XLTM na obrázky v Pythonu" %}}

- Vytvořte objekt třídy [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) pro načtení souboru XLTM
- Použijte třídu [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) a zadejte příslušné možnosti výstupního obrazu
- Získejte přístup k listu pro převod pomocí metody [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Uložte všechny stránky listu jako obrázek pomocí metody [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Nyní je soubor XLTM převeden na obrázky v zadané cestě

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}

- Pro převod XLTM na obrázky (JPG, PNG, GIF, BMP, TIFF) použijte referenční API v rámci projektu přímo z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Nebo použijte následující příkaz pip ```pip install aspose.cells``` 
- Navíc si stáhněte balíček API ze sekce [Stahování](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Převod XLTM na obrázky přes Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}