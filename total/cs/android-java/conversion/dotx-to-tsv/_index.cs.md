---
title: Android API pro převod DOTX na TSV
description: Převeďte DOTX na TSV v Androidu přes Java bez použití Microsoft Word nebo Microsoft Excel
url: /cs/android-java/conversion/dotx-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: TSV
otherformats: EXCEL XLTX SXC DIF FODS XLSX XLAM XLSB XLSM ODS XLT CSV XLS XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte DOTX na TSV v aplikacích pro Android" h2="Export DOTX do TSV v Androidu přes Java bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) můžete integrovat funkci převodu DOTX na TSV do svých aplikací pro Android. Za prvé, můžete převést DOTX do HTML pomocí rozhraní API pro manipulaci s dokumenty a konverzi s bohatými funkcemi [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/). Poté můžete pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) převést HTML na TSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API pro převod DOTX na TSV" %}}
1. Otevřete soubor DOTX pomocí třídy [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
2. Převeďte DOTX do HTML pomocí [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Načtěte dokument HTML pomocí třídy [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu TSV pomocí [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Cells for Android via Java](https://dotxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) a [Aspose.Words pro Android přes Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odstraňte nepoužité informace z dokumentu DOTX v systému Android pomocí Java" %}}
Před převodem DOTX na TSV můžete z dokumentu DOTX odstranit nepoužité informace prostřednictvím [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/). Někdy může být nutné odstranit nepoužívané nebo duplicitní informace, aby se snížila velikost výstupního dokumentu a doba zpracování. Třída [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) umožňuje zadat možnosti čištění dokumentů. Chcete-li z dokumentu odstranit duplicitní styly nebo pouze nepoužívané styly nebo seznamy, můžete použít metodu [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#cleanup()). Můžete použít [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) a [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pro detekci a odstranění stylů, které jsou označeny jako „nepoužité“.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložte soubor TSV pro streamování v systému Android přes Java" %}}
Po převedení DOTX do TSV vám [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/) umožní uložit dokument ke streamování. Pokud potřebujete uložit soubory do streamu, měli byste vytvořit objekt FileOutputStream a poté [uložit](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) soubor do tohoto objektu Stream voláním metody uložení [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-excel/" name="DOTX Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xltx/" name="DOTX Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-sxc/" name="DOTX Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-dif/" name="DOTX Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-fods/" name="DOTX Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xlsx/" name="DOTX Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xlam/" name="DOTX Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xlsb/" name="DOTX Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xlsm/" name="DOTX Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-ods/" name="DOTX Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xlt/" name="DOTX Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-tsv/" name="DOTX Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xls/" name="DOTX Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/dotx-to-xltm/" name="DOTX Na XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}