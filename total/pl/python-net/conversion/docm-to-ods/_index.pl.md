---
title: Konwertuj DOCM na ODS za pomocą Pythona
description: Konwersja DOCM na ODS w aplikacjach Pythona bez użycia Microsoft Word lub Excel 

family: total
platformtag: Python
feature: conversion
informat: DOCM
outformat: ODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj DOCM na ODS za pomocą Pythona" h2="Konwersja DOCM na ODS w aplikacjach Pythona bez instalowania Microsoft Word<sup>&reg;</sup> lub Excela" >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, który próbuje dodać funkcję konwersji DOCM do ODS w aplikacji. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty.

To głównie w dwóch krokach. Najpierw użyj [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API do konwersji pliku DOCM na HTML. Następnie za pomocą Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) zapisz utworzony kod HTML w żądanym formacie Microsoft Excel. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować DOCM na ODS w Pythonie" %}}
- **Krok 1** Otwórz źródłowy plik DOCM przy użyciu klasy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Zapisz plik DOCM do formatu HTML, używając metody [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/), podając nazwę pliku i żądaną ścieżkę do katalogu
-  **Krok 2** Załaduj plik HTML z instancją klasy Workbook z parametrami file i LoadOptions
-  Wywołaj metodę `save` podczas określania wyjściowej ścieżki pliku ODS. Więc twój plik DOCM jest konwertowany na ODS w określonej ścieżce

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania konwersji" %}}

- Do konwersji DOCM na ODS wymagany jest Python 3.5 lub nowszy
- Odwołaj się do API w ramach projektu bezpośrednio z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) i [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Lub użyj następujących poleceń pip ```pip install aspose.words``` i ```pip install aspose-cells-python``` 
-  Ponadto system operacyjny Microsoft Windows lub Linux (zobacz więcej dla [Words](https://docs.aspose.com/words/python-net/system-requirements/) i [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) oraz Linux sprawdź dodatkowe wymagania dla gcc i libpython i postępuj zgodnie z [instrukcje krok po kroku](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz DOCM do HTML w Pythonie - krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zapisz HTML do ODS w Pythonie - krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}