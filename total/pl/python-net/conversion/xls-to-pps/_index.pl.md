---
title: Konwertuj XLS na PPS za pomocą Pythona
description: Konwersja XLS na PPS w aplikacjach Pythona bez użycia pakietu Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLS
outformat: PPS
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj XLS na PPS za pomocą Pythona" h2="Konwersja XLS na PPS w aplikacjach Pythona bez instalowania Microsoft Excel<sup>&reg;</sup> lub PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, który próbuje dodać funkcję konwersji XLS do PPS w aplikacji, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym pliki XLS i PPS.

To głównie w dwóch krokach. Najpierw użyj API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), aby przekonwertować plik XLS na PDF. Następnie za pomocą PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) zapisz utworzony plik PDF w żądanym formacie Microsoft PowerPoint. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować XLS na PPS w Pythonie" %}}
- **Krok 1** Użyj instancji klasy Workbook, aby otworzyć źródłowy plik XLS 
- Zapisz plik XLS do formatu PDF przy użyciu metody save, podając nazwę pliku i żądaną ścieżkę do katalogu
-  **Krok 2** Załaduj plik PDF przy użyciu klasy [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Wywołaj metodę [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/), określając ścieżkę wyjściowego pliku PPS. Więc twój plik XLS jest konwertowany na PPS w określonej ścieżce

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania konwersji" %}}

- Do konwersji XLS na PPS wymagany jest Python 3.5 lub nowszy
- Odwołaj się do API w ramach projektu bezpośrednio z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) i [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Lub użyj następujących poleceń pip ```pip install aspose-cells-python``` i ```pip install aspose.slides```
-  Ponadto system operacyjny oparty na Microsoft Windows lub Linux (zobacz więcej dla [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) i [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz XLS do PDF w Pythonie - krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zapisz plik PDF do formatu PPS w Pythonie — krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}