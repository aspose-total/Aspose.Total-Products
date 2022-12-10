---
title: Android API 將 WORD 轉換為 CSV
description: 在不使用 Microsoft Word 或 Microsoft Excel 的情況下，通過 Java 在 Android 中將 WORD 轉換為 CSV

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: CSV
otherformats: XLAM XLS EXCEL XLTX ODS XLT XLSB XLSX TSV SXC DIF XLSM XLTM FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 應用程序中將 WORD 轉換為 CSV" h2="在不使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 的情況下，通過 Java 在 Android 中將 WORD 導出為 CSV" >}}

{{% blocks/products/pf/feature-page-summary %}}
通過使用 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)，您可以在您的 android 應用程序中集成 WORD 到 CSV 轉換功能。首先，您可以使用功能豐富的文檔操作和轉換 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)將 WORD 轉換為 HTML。之後，通過使用 [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)，您可以將 HTML 轉換為 CSV。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API 將 WORD 轉換為 CSV" %}}
1. 使用 [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument) 類打開 WORD 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) 將 WORD 轉換為 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載 HTML 文檔
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.)) 將文檔保存為 CSV 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Cells for Android](https://words.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) 和 [Aspose.Words for Android via Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository)在您的應用程序中。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 從 Android 中的 WORD 文檔中刪除未使用的信息" %}}
在將 WORD 轉換為 CSV 之前，您可以通過 [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) 從 WORD 文檔中刪除未使用的信息。有時您可能需要刪除未使用或重複的信息以減少輸出文檔的大小和處理時間。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) 類允許您指定文檔清理的選項。要從文檔中刪除重複的樣式或只是未使用的樣式或列表，您可以使用 [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Wordument#cleanup()) 方法。您可以使用 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 和 [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 屬性來檢測和刪除標記為“未使用”的樣式。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-wordument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 將 CSV 文件保存到 Android 中的流" %}}
將 WORD 轉換為 CSV 後，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 使您能夠將文檔保存為流式傳輸。如果您需要將文件保存到 Stream，那麼您應該創建一個 FileOutputStream 對象，然後 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) 通過調用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 的 save 方法將文件保存到該 Stream 對象目的。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xlam/" name="WORD 至 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xls/" name="WORD 至 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-excel/" name="WORD 至 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xltx/" name="WORD 至 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-ods/" name="WORD 至 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xlt/" name="WORD 至 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xlsb/" name="WORD 至 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xlsx/" name="WORD 至 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-tsv/" name="WORD 至 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-sxc/" name="WORD 至 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-dif/" name="WORD 至 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xlsm/" name="WORD 至 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-xltm/" name="WORD 至 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/word-to-fods/" name="WORD 至 FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}