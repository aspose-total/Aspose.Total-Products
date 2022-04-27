---
title: Java API pro převod RTF do ODS
description: Převeďte RTF na ODS přes Java bez použití Microsoft Word nebo Microsoft Excel
url: /cs/java/conversion/rtf-to-ods/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: ODS
otherformats: XLTM DIF TSV XLSB XLTX XLAM FODS XLSM XLS EXCEL XLSX SXC ODS XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést RTF na ODS přes Java" h2="On Premise Java API pro převod RTF na ODS bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Převod RTF na ODS prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/) je jednoduchý dvoufázový proces. Pomocí rozhraní API pro manipulaci s dokumenty a konverzi [Aspose.Words for Java](https://products.aspose.com/words/java/) můžete exportovat RTF do HTML. Poté můžete pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) převést HTML na ODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod RTF do ODS" %}}
1. Otevřete soubor RTF pomocí třídy [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Převeďte RTF do HTML pomocí [Save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
3. Načtěte dokument HTML pomocí třídy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu ODS pomocí [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.Words for Java](https://rtfs.aspose.com/words/java/installation/) a [Aspose.Cells for Java](https://rtfs.aspose.com/cells/java/ instalace/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Před převodem RTF na ODS můžete z dokumentu RTF odstranit nepoužité informace prostřednictvím [Aspose.Words for Java](https://products.aspose.com/words/java/). Někdy může být nutné odstranit nepoužívané nebo duplicitní informace, aby se snížila velikost výstupního dokumentu a doba zpracování. Třída [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) umožňuje zadat možnosti čištění dokumentů. Chcete-li z dokumentu odstranit duplicitní styly nebo jen nepoužívané styly nebo seznamy, můžete použít metodu [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). Můžete použít [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) a [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pro detekci a odstranění stylů, které jsou označeny jako „nepoužité“.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Odstraňte nepoužité informace z dokumentu RTF pomocí Java" %}}
Po převodu RTF do ODS vám [Aspose.Cells for Java](https://products.aspose.com/cells/java/) umožní uložit dokument ke streamování. Pokud potřebujete uložit soubory do streamu, měli byste vytvořit objekt FileOutputStream a poté [uložit](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) soubor do tohoto objektu Stream voláním metody uložení [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlsm/" name="RTF Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlt/" name="RTF Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-ods/" name="RTF Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-tsv/" name="RTF Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xls/" name="RTF Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlsb/" name="RTF Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-fods/" name="RTF Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-dif/" name="RTF Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xltx/" name="RTF Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlam/" name="RTF Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlsx/" name="RTF Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xltm/" name="RTF Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-sxc/" name="RTF Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-excel/" name="RTF Na EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}