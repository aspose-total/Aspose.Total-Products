---
title: Konwertuj XLT na MOBI za pomocą Pythona
description: Konwersja XLT na MOBI w aplikacjach Pythona bez użycia pakietu Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLT
outformat: MOBI
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj XLT na MOBI za pomocą Pythona" h2="Konwersja XLT na MOBI w aplikacjach Pythona bez instalowania programu Microsoft Excel<sup>&reg;</sup> lub programu Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, który próbuje dodać funkcję konwersji XLT do MOBI w aplikacji. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym pliki XLT i MOBI.

To głównie w dwóch krokach. Najpierw użyj interfejsu API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), aby przekonwertować plik XLT na HTML. Następnie za pomocą Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) zapisz utworzony kod HTML w żądanym formacie Microsoft Word. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować XLT na MOBI w Pythonie" %}}
- **Krok 1** Otwórz źródłowy plik XLT przy użyciu klasy Workbook
- Zapisz plik XLT do formatu HTML, używając metody save(file, SaveFormat.HTML), podając nazwę pliku i żądaną ścieżkę do katalogu
-  **Krok 2** Załaduj plik HTML z instancją klasy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Wywołaj metodę `save` podczas określania wyjściowej ścieżki pliku MOBI. Więc twój plik XLT jest konwertowany na MOBI w określonej ścieżce

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania konwersji" %}}

- Do konwersji XLT na MOBI wymagany jest Python 3.5 lub nowszy
- Odwołaj się do API w ramach projektu bezpośrednio z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) i [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Lub użyj następujących poleceń pip ```pip install aspose-cells-python``` i ```pip install aspose.words```
-  Ponadto system operacyjny oparty na Microsoft Windows lub Linux (zobacz więcej dla [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) i [Words](https://docs.aspose.com/words/python-net/system-requirements/)) oraz Linux sprawdź dodatkowe wymagania dla gcc i libpython i postępuj zgodnie z [instrukcje krok po kroku](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz XLT do HTML w Pythonie - krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zapisz HTML do MOBI w Pythonie - krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}