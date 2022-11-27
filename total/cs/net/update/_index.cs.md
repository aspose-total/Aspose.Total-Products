---
title: Aktualizujte soubory Excel pomocí .NET 

description: Upravujte dokumenty Microsoft Excel XLSX, XLS, CSV bez instalace Microsoft Office s aplikacemi založenými na C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte dokumenty Excel přes .NET" h2="Upravujte soubory Microsoft Excel XLSX, XLS v aplikacích založených na .NET bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Je běžné, že organizace aktualizují svá data uložená v excelových souborech, jako jsou data studentů, záznamy pacientů a seznam skladových položek atd. prostřednictvím firemního softwaru. [Aspose.Total for .NET](https://products.aspose.com/total/net/) API poskytuje funkce úpravy tabulek pomocí softwaru. Programátoři mohou vylepšit software pomocí možností úprav pouhým napsáním několika řádků kódu API. [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API, které je součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net/), usnadňuje tento proces úpravy. Níže je uveden postup aktualizace dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualizujte dokumenty Excel pomocí .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API poskytuje třídu Workbook, která zpracovává načítání excelových tabulek. Proces je jednoduchý. Vytvořte objekt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) zadáním zdrojového souboru jako parametru. Získejte přístup k příslušnému listu poskytnutím jeho indexu pomocí metody [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Pomocí metody [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) upravte obsah v buňce, ke které se přistupuje, a nakonec zavolejte metodu save() pro uložení dokumentu.

{{% blocks/products/pf/feature-page-code h3=".NET Code – aktualizujte dokumenty aplikace Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizace">}}