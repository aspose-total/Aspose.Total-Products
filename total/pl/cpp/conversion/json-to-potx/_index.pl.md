---
title: Konwertuj format JSON na POTX za pomocą C++
description: Przetwarzaj JSON do POTX w C++ bez użycia programu Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTX
otherformats: OTP PPTM PPSM ODP PPSX PPS POT POTM POWERPOINT PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj format JSON na POTX za pomocą C++" h2="C++ API do parsowania JSON do POTX bez użycia Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować JSON na POTX w dowolnej aplikacji C++ w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), możesz przetworzyć JSON na PPTX. Następnie, używając [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), możesz przekonwertować PPTX na POTX. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na POTX za pomocą C++" %}}
1. Utwórz nowy obiekt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zapisz JSON jako PPTX za pomocą metody [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Zapisz dokument w formacie POTX za pomocą metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na POTX za pomocą C++" %}}
Podczas parsowania JSON do POTX możesz również ustawić rozmiar wierszy i kolumn, ładując JSON za pomocą klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Jeśli chcesz ustawić tę samą wysokość wiersza dla wszystkich wierszy w arkuszu, możesz to zrobić za pomocą [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metoda kolekcji [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Podobnie, aby ustawić tę samą szerokość kolumny dla wszystkich kolumn w arkuszu, użyj metody [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) kolekcji ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj format JSON na POTX za pomocą znaku wodnego w C++" %}}
Korzystając z API, możesz również przekonwertować JSON na POTX ze znakiem wodnym. Aby dodać znak wodny do dokumentu POTX, możesz najpierw przeanalizować JSON do PPTX i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), pobierz pierwszy slajd, Dodaj Autokształt typu Rectangle, dodaj TextFrame do Rectangle, utwórz obiekt Akapit dla ramki tekstowej, utwórz obiekt Portion dla akapitu, dodaj znak wodny za pomocą set_Text() i zapisz dokument w formacie POTX.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}