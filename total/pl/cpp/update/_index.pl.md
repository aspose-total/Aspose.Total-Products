---
title: Zaktualizuj pliki programu Excel przy użyciu języka C++ 

description: Edytuj dokumenty Microsoft Excel XLSX, XLS, CSV bez instalowania pakietu Microsoft Office z aplikacjami opartymi na C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Zaktualizuj dokumenty programu Excel za pomocą C++" h2="Modyfikuj pliki Microsoft Excel XLSX, XLS w aplikacjach opartych na C++ bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Organizacje często aktualizują swoje dane przechowywane w plikach programu Excel, takie jak dane uczniów, dane pacjentów i listy pozycji magazynowych itp. Za pośrednictwem oprogramowania firmowego. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API zapewnia funkcjonalność modyfikacji arkuszy kalkulacyjnych za pomocą oprogramowania. Programiści mogą wzbogacić oprogramowanie o możliwości modyfikacji, pisząc po prostu kilka linijek kodu API. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, które jest częścią pakietu [Aspose.Total for C++](https://products.aspose.com/total/cpp/), ułatwia ten proces modyfikacji. Poniżej przedstawiono proces aktualizacji dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zaktualizuj dokumenty programu Excel przy użyciu języka C++" %}}

Korzystając z interfejsu API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), załaduj dokument źródłowy za pomocą [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Uzyskaj dostęp do [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) za pomocą GetIWorksheets()->GetObjectByIndex(0) i wymaganej komórki za pomocą GetICells()->GetObjectByIndex. Korzystając z metody PutValue, zmodyfikuj zawartość w otwieranej komórce. Na koniec wywołaj metodę save(), aby zapisać dokument.

{{% blocks/products/pf/feature-page-code h3="Kod C++ — aktualizacja dokumentów programu Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizacja">}}