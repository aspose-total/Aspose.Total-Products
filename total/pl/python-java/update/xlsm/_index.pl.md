---
title: Zaktualizuj plik XLSM za pomocą Pythona
description: Modyfikuj dokument XLSM w aplikacjach Python bez użycia programu Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj plik XLSM za pomocą Pythona" h2="Modyfikuj arkusze kalkulacyjne XLSM za pomocą aplikacji Python bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty, który próbuje aktualizować pliki XLSM za pomocą aplikacji Python? API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) może pomóc zautomatyzować proces aktualizacji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym pliki Microsoft Excel. API ASPOSE.CELL będące częścią pakietu [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) ułatwia ten proces modyfikacji. Poniżej znajduje się proces aktualizacji dokumentu XLSM.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak zaktualizować plik XLSM w Pythonie?" %}}

- Utwórz nowy obiekt klasy [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) mając jako parametr źródłowy plik XLSM
- Dostęp do odpowiedniego Arkusza przy użyciu metody [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Wstaw nowe dane do wybranej komórki za pomocą metody [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Zapisz plik jako plik .xlsm za pomocą metody save() przekazując plik ze ścieżką jako parametrem

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące modyfikacji" %}}

- W przypadku modyfikacji XLSM odwołaj się do API w projekcie bezpośrednio z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Lub użyj następującego polecenia pip ```pip install aspose.cells``` 
- Ponadto pobierz pakiet API z sekcji [Pliki do pobrania](https://releases.aspose.comcells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod — aktualizacja pliku XLSM w Pythonie" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}