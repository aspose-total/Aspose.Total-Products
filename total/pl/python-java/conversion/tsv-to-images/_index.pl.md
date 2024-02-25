---
title: Konwertuj TSV na obraz za pomocą Pythona
description: TSV do obrazu TIFF BMP PNG JPEG GIF EMF Konwersja SVG w aplikacjach Pythona bez użycia programu Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj TSV na obraz za pomocą Pythona" h2="Konwersja obrazów TSV do JPG, TIFF, BMP, PNG, GIF w aplikacjach Pythona bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, który próbuje dodać TSV do PNG, BMP, TIFF, JPEG i GIF Funkcja konwersji obrazu w aplikacji. Jak czasami wymagane jest osadzenie arkuszy kalkulacyjnych Excel w aplikacjach internetowych lub desktopowych. W takich przypadkach eksportowanie arkuszy kalkulacyjnych do obrazów jest jedynym rozwiązaniem. API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) może pomóc w eksporcie plików Excel do obrazów, a także zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym formaty Microsoft Excel, za pośrednictwem jego podrzędnego API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/). Obecnie Python Excel to Image Converter API obsługuje konwersję plików Excela na EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM i Office Compatible EMF lub sprawdź obsługiwany [Formaty](https://docs.aspose.com/cells/python-java/supported-file-formats/). 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować TSV na obrazy w Pythonie?" %}}

- Utwórz obiekt klasy [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook), aby załadować plik TSV
- Użyj klasy [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) i określ odpowiednie opcje obrazu wyjściowego
- Uzyskaj dostęp do arkusza kalkulacyjnego do konwersji za pomocą metody [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Zapisz wszystkie strony arkusza roboczego jako obraz przy użyciu metody [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Teraz plik TSV jest konwertowany na obrazy w określonej ścieżce

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}

- W przypadku konwersji TSV na obrazy (JPG, PNG, GIF, BMP, TIFF) odwołaj się do interfejsów API w projekcie bezpośrednio z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Lub użyj następującego polecenia pip ```pip install aspose.cells``` 
- Ponadto pobierz pakiet API z sekcji [Pliki do pobrania](https://releases.aspose.comcells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Konwersja TSV do obrazów za pomocą Pythona" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}