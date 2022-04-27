---
title: Java API pro převod ODT do TSV
description: Převeďte ODT na TSV přes Java bez použití Microsoft Word nebo Microsoft Excel
url: /cs/java/conversion/odt-to-tsv/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: TSV
otherformats: XLTM ODS XLSM TSV XLS XLSX EXCEL SXC XLSB XLT XLAM XLTX DIF FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést ODT na TSV přes Java" h2="On Premise Java API pro převod ODT na TSV bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Převod ODT na TSV prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/) je jednoduchý dvoufázový proces. Pomocí rozhraní API pro manipulaci s dokumenty a konverzi [Aspose.Words for Java](https://products.aspose.com/words/java/) můžete exportovat ODT do HTML. Poté můžete pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) převést HTML na TSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod ODT do TSV" %}}
1. Otevřete soubor ODT pomocí třídy [Odtument](https://apireference.aspose.com/words/java/com.aspose.words/Odtument)
2. Převeďte ODT do HTML pomocí [Save](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
3. Načtěte dokument HTML pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu TSV pomocí [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.Words for Java](https://odts.aspose.com/words/java/installation/) a [Aspose.Cells for Java](https://odts.aspose.com/cells/java/ instalace/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Před převodem ODT na TSV můžete z dokumentu ODT odstranit nepoužité informace prostřednictvím [Aspose.Words for Java](https://products.aspose.com/words/java/). Někdy může být nutné odstranit nepoužívané nebo duplicitní informace, aby se snížila velikost výstupního dokumentu a doba zpracování. Třída [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) umožňuje zadat možnosti čištění dokumentů. Chcete-li z dokumentu odstranit duplicitní styly nebo jen nepoužívané styly nebo seznamy, můžete použít metodu [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#cleanup()). Můžete použít [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) a [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pro detekci a odstranění stylů, které jsou označeny jako „nepoužité“.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-odtument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Odstraňte nepoužité informace z dokumentu ODT pomocí Java" %}}
Po převodu ODT do TSV vám [Aspose.Cells for Java](https://products.aspose.com/cells/java/) umožní uložit dokument ke streamování. Pokud potřebujete uložit soubory do streamu, měli byste vytvořit objekt FileOutputStream a poté [uložit](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) soubor do tohoto objektu Stream voláním metody uložení [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlsm/" name="ODT Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlt/" name="ODT Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-ods/" name="ODT Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-tsv/" name="ODT Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xls/" name="ODT Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlsb/" name="ODT Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-fods/" name="ODT Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-dif/" name="ODT Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xltx/" name="ODT Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlam/" name="ODT Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xlsx/" name="ODT Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-xltm/" name="ODT Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-sxc/" name="ODT Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/odt-to-excel/" name="ODT Na EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}