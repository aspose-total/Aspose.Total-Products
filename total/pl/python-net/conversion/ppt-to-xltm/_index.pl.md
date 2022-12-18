---
title: Konwertuj PPT na XLTM za pomocą Pythona
description: Konwersja PPT na XLTM w aplikacjach Pythona bez użycia pakietu Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPT
outformat: XLTM
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj PPT na XLTM za pomocą Pythona" h2="Konwersja PPT na XLTM w aplikacjach Pythona bez instalowania programu Microsoft PowerPoint<sup>&reg;</sup> lub programu Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, który próbuje dodać funkcję konwersji PPT do XLTM w aplikacji. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym pliki PPT i XLTM.

To głównie w dwóch krokach. Najpierw użyj interfejsu API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), aby przekonwertować plik PPT na HTML. Następnie za pomocą Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) zapisz utworzony kod HTML w żądanym formacie Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować PPT na XLTM w Pythonie" %}}
- **Krok 1** Użyj instancji klasy [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), aby otworzyć źródłowy plik PPT 
- Zapisz plik PPT do formatu HTML, używając metody [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), podając nazwę pliku i żądaną ścieżkę do katalogu
-  **Krok 2** Załaduj plik HTML z instancją klasy Workbook
-  Wywołaj metodę `save` podczas określania wyjściowej ścieżki pliku XLTM. Więc twój plik PPT jest konwertowany na XLTM w określonej ścieżce

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania konwersji" %}}

- Do konwersji PPT na XLTM wymagany jest Python 3.5 lub nowszy
- Odwołaj się do API w ramach projektu bezpośrednio z PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) i [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Lub użyj następujących poleceń pip ```pip install aspose.slides``` i ```pip install aspose-cells-python```
-  Ponadto system operacyjny oparty na Microsoft Windows lub Linux (zobacz więcej dla [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) i [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz PPT do HTML w Pythonie - krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zapisz HTML do XLTM w Pythonie - krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}