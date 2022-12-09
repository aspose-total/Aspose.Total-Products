---
title: Zaktualizuj plik XLSM za pomocą C++
description: Modyfikuj dokument XLSM w aplikacjach C++ bez użycia programu Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj plik XLSM przez C++" h2="Modyfikuj arkusze kalkulacyjne XLSM za pomocą aplikacji opartych na języku C++ bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty, który próbuje zaktualizować pliki XLSM w aplikacji C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API może pomóc zautomatyzować proces aktualizacji. Jest to pełny pakiet różnych bibliotek C++ obsługujących wiele formatów, w tym dokumenty Microsoft Excel. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), które jest częścią pakietu [Aspose.Total for C++](https://products.aspose.com/total/cpp/), ułatwia ten proces modyfikacji. Proces aktualizacji dokumentu XLSM jest prosty poprzez najpierw dostęp do arkusza, a następnie aktualizację wartości komórki w Excelu przy użyciu C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak zaktualizować plik XLSM w C++" %}}

- Załaduj plik XLSM za pomocą [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Dostęp do odpowiedniego [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) przy użyciu GetIWorksheets()->GetObjectByIndex(0) i odpowiedniej komórki przy użyciu GetICells()->GetObjectByIndex
- Wstaw nowe dane do otwieranej komórki metodą PutValue
- Zapisz plik jako plik .xlsm metodą Save przekazując jako parametr plik ze ścieżką

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące modyfikacji" %}}

- Do modyfikacji XLSM, zgodnie z [wymagania systemowe](https://docs.aspose.com/cells/cpp/system-requirements/) dla systemów Windows i Linux 
- Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp```
- Lub przez konsolę Menedżera pakietów programu Visual Studio z ```Install-Package Aspose.Total.Cpp```
- Ewentualnie pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [Pliki do pobrania](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod — aktualizacja pliku XLSM w C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje modyfikacji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xls/" name="Aktualizacja XLS Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xlsx/" name="Aktualizacja XLSX Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/csv/" name="Aktualizacja CSV Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xlsb/" name="Aktualizacja XLSB Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xlsm/" name="Modyfikować XLSM Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xlt/" name="Aktualizacja XLT Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xltx/" name="Aktualizacja XLTX Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/xltm/" name="Aktualizacja XLTM Plik" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/update/tsv/" name="Aktualizacja TSV Plik" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}