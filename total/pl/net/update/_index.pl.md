---
title: Zaktualizuj pliki programu Excel przy użyciu platformy .NET 

description: Edytuj dokumenty Microsoft Excel XLSX, XLS, CSV bez instalowania pakietu Microsoft Office z aplikacjami opartymi na C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj dokumenty programu Excel za pośrednictwem platformy .NET" h2="Modyfikuj pliki Microsoft Excel XLSX, XLS w aplikacjach opartych na platformie .NET bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Organizacje często aktualizują swoje dane przechowywane w plikach programu Excel, takie jak dane uczniów, dane pacjentów i listy pozycji magazynowych itp. Za pośrednictwem oprogramowania firmowego. [Aspose.Total for .NET](https://products.aspose.com/total/net/) API zapewnia funkcjonalność modyfikacji arkuszy kalkulacyjnych za pomocą oprogramowania. Programiści mogą wzbogacić oprogramowanie o możliwości modyfikacji, pisząc po prostu kilka linijek kodu API. [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API, które jest częścią pakietu [Aspose.Total for .NET](https://products.aspose.com/total/net/), ułatwia ten proces modyfikacji. Poniżej przedstawiono proces aktualizacji dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zaktualizuj dokumenty programu Excel przy użyciu platformy .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API udostępnia klasę Workbook, która obsługuje ładowanie arkuszy kalkulacyjnych Excel. Proces jest prosty. Utwórz obiekt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/), podając plik źródłowy jako parametr. Uzyskaj dostęp do odpowiedniego arkusza roboczego, podając jego indeks za pomocą metody [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Użyj metody [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/), aby zmodyfikować zawartość komórki, do której uzyskano dostęp, a na koniec wywołaj metodę save() w celu zapisania dokumentu.

{{% blocks/products/pf/feature-page-code h3="Kod platformy .NET — aktualizacja dokumentów programu Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizacja">}}