---
title: Konwertuj RTF na XLT za pomocą Pythona
description: Konwersja RTF na XLT w aplikacjach Pythona bez użycia Microsoft Word lub Excel 

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: XLT
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj RTF na XLT za pomocą Pythona" h2="Konwersja RTF na XLT w aplikacjach Pythona bez instalowania Microsoft Word<sup>&reg;</sup> lub Excela" >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, który próbuje dodać funkcję konwersji RTF do XLT w aplikacji. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty.

To głównie w dwóch krokach. Najpierw użyj [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API do konwersji pliku RTF na HTML. Następnie za pomocą Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) zapisz utworzony kod HTML w żądanym formacie Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować RTF na XLT w Pythonie" %}}
- **Krok 1** Otwórz źródłowy plik RTF przy użyciu klasy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Zapisz plik RTF do formatu HTML, używając metody [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/), podając nazwę pliku i żądaną ścieżkę do katalogu
-  **Krok 2** Załaduj plik HTML z instancją klasy Workbook z parametrami file i LoadOptions
-  Wywołaj metodę `save` podczas określania wyjściowej ścieżki pliku XLT. Więc twój plik RTF jest konwertowany na XLT w określonej ścieżce

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania konwersji" %}}

- Do konwersji RTF na XLT wymagany jest Python 3.5 lub nowszy
- Odwołaj się do API w ramach projektu bezpośrednio z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) i [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Lub użyj następujących poleceń pip ```pip install aspose.words``` i ```pip install aspose-cells-python``` 
-  Ponadto system operacyjny Microsoft Windows lub Linux (zobacz więcej dla [Words](https://docs.aspose.com/words/python-net/system-requirements/) i [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) oraz Linux sprawdź dodatkowe wymagania dla gcc i libpython i postępuj zgodnie z [instrukcje krok po kroku](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz RTF do HTML w Pythonie - krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zapisz HTML do XLT w Pythonie - krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}