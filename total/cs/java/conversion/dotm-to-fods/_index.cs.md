---
title: Java API pro převod DOTM do FODS
description: Převeďte DOTM na FODS přes Java bez použití Microsoft Word nebo Microsoft Excel
url: /cs/java/conversion/dotm-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: FODS
otherformats: XLT TSV DIF XLSM FODS EXCEL XLSX XLS XLTX ODS SXC XLSB XLTM XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést DOTM na FODS přes Java" h2="On Premise Java API pro převod DOTM na FODS bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Převod DOTM na FODS prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/) je jednoduchý dvoufázový proces. Pomocí rozhraní API pro manipulaci s dokumenty a konverzi [Aspose.Words for Java](https://products.aspose.com/words/java/) můžete exportovat DOTM do HTML. Poté můžete pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) převést HTML na FODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod DOTM do FODS" %}}
1. Otevřete soubor DOTM pomocí třídy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Převeďte DOTM do HTML pomocí [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
3. Načtěte dokument HTML pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu FODS pomocí [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.Words for Java](https://dotms.aspose.com/words/java/installation/) a [Aspose.Cells for Java](https://dotms.aspose.com/cells/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Před převodem DOTM na FODS můžete z dokumentu DOTM odstranit nepoužité informace prostřednictvím [Aspose.Words for Java](https://products.aspose.com/words/java/). Někdy může být nutné odstranit nepoužívané nebo duplicitní informace, aby se snížila velikost výstupního dokumentu a doba zpracování. Třída [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) umožňuje zadat možnosti čištění dokumentů. Chcete-li z dokumentu odstranit duplicitní styly nebo jen nepoužívané styly nebo seznamy, můžete použít metodu [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Můžete použít [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) a [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pro detekci a odstranění stylů, které jsou označeny jako „nepoužité“.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotmument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Odstraňte nepoužité informace z dokumentu DOTM pomocí Java" %}}
Po převodu DOTM do FODS vám [Aspose.Cells for Java](https://products.aspose.com/cells/java/) umožní uložit dokument ke streamování. Pokud potřebujete uložit soubory do streamu, měli byste vytvořit objekt FileOutputStream a poté [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) soubor do tohoto objektu Stream voláním metody uložení [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xlsm/" name="DOTM Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xlt/" name="DOTM Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-ods/" name="DOTM Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-tsv/" name="DOTM Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xls/" name="DOTM Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xlsb/" name="DOTM Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-fods/" name="DOTM Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-dif/" name="DOTM Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xltx/" name="DOTM Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xlam/" name="DOTM Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xlsx/" name="DOTM Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-xltm/" name="DOTM Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-sxc/" name="DOTM Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/dotm-to-excel/" name="DOTM Na EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}