---
title: Zaktualizuj pliki programu Excel przy użyciu języka Java 

description: Edytuj dokumenty Microsoft Excel XLSX, XLS, CSV bez instalowania pakietu Microsoft Office w aplikacjach opartych na Javie.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj dokumenty programu Excel za pomocą języka Java" h2="Modyfikuj pliki Microsoft Excel XLSX, XLS w aplikacjach opartych na Javie bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Organizacje często aktualizują swoje dane przechowywane w plikach programu Excel, takie jak dane uczniów, dane pacjentów i listy pozycji magazynowych itp. Za pośrednictwem oprogramowania firmowego. [Aspose.Total for Java](https://products.aspose.com/total/java/) API zapewnia funkcjonalność modyfikacji arkuszy kalkulacyjnych przy użyciu własnego oprogramowania. Programiści mogą wzbogacić oprogramowanie o możliwości modyfikacji, pisząc po prostu kilka linijek kodu API. [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API, które jest częścią pakietu [Aspose.Total for Java](https://products.aspose.com/total/java/), ułatwia ten proces modyfikacji. Poniżej przedstawiono proces aktualizacji dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zaktualizuj dokumenty programu Excel przy użyciu języka Java" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API udostępnia klasę [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook), która obsługuje ładowanie arkuszy kalkulacyjnych Excel. Proces jest prosty. Utwórz obiekt klasy Workbook, podając plik źródłowy jako parametr. Uzyskaj dostęp do odpowiedniego arkusza roboczego i odpowiedniej komórki za pomocą metody [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Użyj metody [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value), aby zmodyfikować zawartość komórki, do której uzyskano dostęp, a na koniec wywołaj metodę save() w celu zapisania dokumentu.

{{% blocks/products/pf/feature-page-code h3="Kod Java - Aktualizuj dokumenty programu Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizacja">}}