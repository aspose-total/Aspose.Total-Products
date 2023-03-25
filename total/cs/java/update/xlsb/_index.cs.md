---
title: Aktualizujte soubor XLSB pomocí Javy
description: Upravte dokument XLSB v aplikacích Java bez použití aplikace Microsoft Excel. Optimalizujte kód pro nejrychlejší způsob zápisu a úpravy excelového souboru v Javě.

family: total
platformtag: Java
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualizujte soubor XLSB přes Java" h2="Upravujte tabulky XLSB prostřednictvím aplikací založených na Javě bez instalace Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře, který se snaží aktualizovat soubory XLSB v jakékoli aplikaci Java? [Aspose.Total for Java](https://products.aspose.com/total/java/) API může pomoci automatizovat proces aktualizace. Jedná se o úplný balík různých Java API zabývajících se více formáty včetně dokumentů Microsoft Excel. ASPOSE.CELL API, které je součástí balíčku [Aspose.Total for Java](https://products.aspose.com/total/java/), usnadňuje tento proces úpravy. Proces aktualizace dokumentu XLSB je jednoduchý tím, že nejprve zpřístupníte list a poté aktualizujete hodnotu buňky v Excelu pomocí Java.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak aktualizovat soubor XLSB v Javě" %}}

- Vytvořte nový objekt třídy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) se zdrojovým souborem XLSB jako parametrem
- Přístup k příslušnému pracovnímu listu a příslušné buňce pomocí metody [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int))
- Pomocí metody [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) vložte nová data do přístupné buňky
- Uložte soubor jako soubor .xlsb pomocí metody save() předáním souboru s cestou jako parametrem

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na úpravu" %}}

- Pro modifikaci XLSB, Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- J2SE 6.0 (1.6), J2SE 7.0 (1.7) nebo vyšší.
- Získejte nejnovější verzi API přímo z [Stahování](https://docs.aspose.com/cells/java/installation/)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód - Aktualizujte soubor XLSB v Javě" offSpacer="" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}