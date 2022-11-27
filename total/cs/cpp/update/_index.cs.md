---
title: Aktualizujte soubory Excel pomocí C++ 

description: Upravujte dokumenty Microsoft Excel XLSX, XLS, CSV bez instalace Microsoft Office s aplikacemi založenými na C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte dokumenty Excel přes C++" h2="Upravujte soubory Microsoft Excel XLSX, XLS v aplikacích založených na C++ bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Je běžné, že organizace aktualizují svá data uložená v excelových souborech, jako jsou data studentů, záznamy pacientů a seznam skladových položek atd. prostřednictvím firemního softwaru. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API poskytuje funkce úpravy tabulek pomocí softwaru. Programátoři mohou vylepšit software pomocí možností úprav pouhým napsáním několika řádků kódu API. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, které je součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/), usnadňuje tento proces úpravy. Níže je uveden postup aktualizace dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualizujte dokumenty Excel pomocí C++" %}}

Pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API načtěte zdrojový dokument pomocí [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Přístup k [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) pomocí GetIWorksheets()->GetObjectByIndex(0) a požadované buňky pomocí GetICells()->GetObjectByIndex. Pomocí metody PutValue upravte obsah v buňce, ke které se přistupuje. Nakonec vyvolejte metodu save() pro uložení dokumentu.

{{% blocks/products/pf/feature-page-code h3="Kód C++ - Aktualizujte dokumenty aplikace Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizace">}}