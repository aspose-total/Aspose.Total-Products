---
title: Aktualizujte soubory Excel pomocí Java 

description: Upravujte dokumenty Microsoft Excel XLSX, XLS, CSV bez instalace Microsoft Office v rámci aplikací založených na Javě.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte dokumenty aplikace Excel přes Java" h2="Upravujte soubory Microsoft Excel XLSX, XLS v aplikacích založených na Javě bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Je běžné, že organizace aktualizují svá data uložená v excelových souborech, jako jsou data studentů, záznamy pacientů a seznam skladových položek atd. prostřednictvím firemního softwaru. [Aspose.Total for Java](https://products.aspose.com/total/java/) API poskytuje funkce úpravy tabulek pomocí jejich vlastního softwaru. Programátoři mohou vylepšit software pomocí možností úprav pouhým napsáním několika řádků kódu API. [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API, které je součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/), usnadňuje tento proces úpravy. Níže je uveden postup aktualizace dokumentu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualizujte dokumenty Excel pomocí Javy" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API poskytuje třídu [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook), která zpracovává načítání excelových tabulek. Proces je jednoduchý. Vytvořte objekt třídy Workbook poskytnutím zdrojového souboru jako parametru. Přístup k příslušnému listu a příslušné buňce pomocí metody [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Pomocí metody [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) upravte obsah v buňce, ke které se přistupuje, a nakonec zavolejte metodu save() pro uložení dokumentu.

{{% blocks/products/pf/feature-page-code h3="Java Code - Aktualizace dokumentů aplikace Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualizace">}}