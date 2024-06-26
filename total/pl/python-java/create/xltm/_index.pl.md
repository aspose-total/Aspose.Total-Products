---
title: Utwórz XLTM w Pythonie
description: Generuj plik XLTM za pomocą aplikacji Python bez korzystania z pakietu Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Twórz XLTM za pomocą Pythona" h2="Generuj XLTM za pomocą aplikacji Pythona bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty, który próbuje tworzyć pliki XLTM za pomocą aplikacji Python? API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) może pomóc zautomatyzować proces tworzenia. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym pliki Microsoft Office i obrazy. API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) będące częścią pakietu [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) ułatwia ten proces generowania. Poniżej znajduje się proces tworzenia. Co więcej, programiści mogą łatwo ulepszyć aplikację do modyfikacji pliku XLTM. Aktualizacja pliku XLTM przy użyciu procesu Pythona jest taka sama, z wyjątkiem tego, że wymaga istniejącego pliku jako parametru podczas tworzenia obiektu Workbook.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć plik XLTM w Pythonie?" %}}

- Utwórz nowy obiekt klasy [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) z parametrem PlikFormatType
- Uzyskaj dostęp do wymaganego [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) za pomocą metody [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Wstaw dane do wybranej komórki za pomocą metody [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Zapisz dokument jako plik .xltm za pomocą [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String), przekazując plik ze ścieżką jako parametrem

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące tworzenia" %}}

- W przypadku generowania XLTM odwołaj się do interfejsów API w projekcie bezpośrednio z PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Lub użyj następującego polecenia pip ```pip install aspose.cells``` 
- Ponadto pobierz pakiet API z sekcji [downloads](https://releases.aspose.comcells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Utwórz XLTM w Pythonie" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}