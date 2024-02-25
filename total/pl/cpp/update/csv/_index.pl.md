---
title: Zaktualizuj plik CSV za pomocą C++
description: Modyfikuj dokument CSV w aplikacjach C++ bez użycia programu Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj plik CSV przez C++" h2="Modyfikuj arkusze kalkulacyjne CSV za pomocą aplikacji opartych na języku C++ bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty, który próbuje zaktualizować pliki CSV w aplikacji C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API może pomóc zautomatyzować proces aktualizacji. Jest to pełny pakiet różnych bibliotek C++ obsługujących wiele formatów, w tym dokumenty Microsoft Excel. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), które jest częścią pakietu [Aspose.Total for C++](https://products.aspose.com/total/cpp/), ułatwia ten proces modyfikacji. Proces aktualizacji dokumentu CSV jest prosty poprzez najpierw dostęp do arkusza, a następnie aktualizację wartości komórki w Excelu przy użyciu C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak zaktualizować plik CSV w C++" %}}

- Załaduj plik CSV za pomocą [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Dostęp do odpowiedniego [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) przy użyciu GetIWorksheets()->GetObjectByIndex(0) i odpowiedniej komórki przy użyciu GetICells()->GetObjectByIndex
- Wstaw nowe dane do otwieranej komórki metodą PutValue
- Zapisz plik jako plik .csv metodą Save przekazując jako parametr plik ze ścieżką

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące modyfikacji" %}}

- Do modyfikacji CSV, zgodnie z [wymagania systemowe](https://docs.aspose.com/cells/cpp/system-requirements/) dla systemów Windows i Linux 
- Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp```
- Lub przez konsolę Menedżera pakietów programu Visual Studio z ```Install-Package Aspose.Total.Cpp```
- Ewentualnie pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [Pliki do pobrania](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod — aktualizacja pliku CSV w C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}