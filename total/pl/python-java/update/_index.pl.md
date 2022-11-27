---
title: Zaktualizuj pliki Excela za pomocą Pythona 

description: Edytuj dokumenty Microsoft Excel XLSX, XLS, CSV bez instalowania pakietu Microsoft Office w aplikacjach Pythona
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj dokumenty programu Excel za pomocą Pythona" h2="Modyfikuj pliki Microsoft Excel XLSX, XLS w aplikacjach Pythona bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Organizacje często aktualizują swoje dane przechowywane w plikach programu Excel, takie jak dane uczniów, kartoteki pacjentów i listy pozycji magazynowych itp. Za pośrednictwem oprogramowania firmowego. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API zapewnia funkcjonalność modyfikacji arkuszy kalkulacyjnych za pośrednictwem oprogramowania. Programiści mogą wzbogacić oprogramowanie o możliwości modyfikacji, integrując API i pisząc kilka linijek kodu. API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/), które jest częścią pakietu [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), ułatwia ten proces modyfikacji. Poniżej przedstawiono proces aktualizacji dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zaktualizuj dokumenty programu Excel przy użyciu języka Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API udostępnia klasę Workbook, która obsługuje ładowanie arkuszy kalkulacyjnych Excel. Proces jest prosty. Utwórz obiekt klasy [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook), podając plik źródłowy jako parametr. Użyj metody [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets), aby uzyskać dostęp do odpowiedniego Arkusza, podając jego indeks. wywołaj metodę [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells), aby zmodyfikować zawartość komórki, do której uzyskano dostęp, i na koniec wywołaj metodę save() w celu zapisania dokumentu.

{{% blocks/products/pf/feature-page-code h3="Python — aktualizuj dokumenty programu Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizacja">}}