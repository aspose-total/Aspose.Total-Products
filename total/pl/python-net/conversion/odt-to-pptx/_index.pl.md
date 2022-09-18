---
title: Konwertuj ODT na PPTX w Pythonie
description: Konwersja ODT do PPTX w aplikacjach Pythona bez użycia Microsoft Word lub PowerPoint 
url: /pl/python-net/conversion/odt-to-pptx/
family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: PPTX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj ODT na PPTX za pomocą Pythona" h2="Konwersja ODT do PPTX w aplikacjach Pythona bez instalowania Microsoft Word<sup>&reg;</sup> lub PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, kto próbuje dodać funkcję konwersji ODT do PPTX w aplikacji? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty. Więc **Jak przekonwertować ODT na PPTX w Pythonie?**

To głównie w dwóch krokach. Najpierw użyj API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), aby przekonwertować plik ODT na PDF. Następnie za pomocą programu PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) zapisz utworzony plik PDF w Presentation jako format PPTX. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj ODT na PPTX w Pythonie" %}}
- **Krok 1** Otwórz źródłowy plik ODT przy użyciu klasy ASSOSE.WORDS.DOCUMENT
- Zapisz plik ODT w formacie PDF za pomocą metody [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/), podając nazwę pliku i żądaną ścieżkę katalogu.
-  **Krok 2** Załaduj plik PDF z instancją klasy APOSSE.SLIDES.PRESENTATION
-  Wywołaj metodę `save`, określając ścieżkę pliku wyjściowego i SaveFormat.PPTX jako parametry. Więc twój plik ODT jest konwertowany na PPTX w określonej ścieżce.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}

- Do konwersji ODT na PPTX wymagany jest Python 3.5 lub nowszy
- Odwołaj się do API w ramach projektu bezpośrednio z PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) i [Aspose.Words](https://pypi.org/project/aspose-words/)) lub
- Użyj następujących poleceń pip ```pip install aspose.slides``` i ```pip install aspose.words```. Ponadto,
- System operacyjny oparty na Microsoft Windows lub Linux (zobacz więcej dla [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) i [Words](https://docs.aspose.com/words/python-net/system-requirements/)) oraz dla Linuxa sprawdź dodatkowe wymagania dla gcc i libpython i postępuj zgodnie z instrukcjami krok po kroku [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz ODT do PDF w Pythonie - krok 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zapisz PDF do PPTX w Pythonie - Krok 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}