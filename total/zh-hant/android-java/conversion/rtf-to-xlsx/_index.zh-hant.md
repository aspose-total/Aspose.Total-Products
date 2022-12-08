---
title: Android API 將 RTF 轉換為 XLSX
description: 在不使用 Microsoft Word 或 Microsoft Excel 的情況下，通過 Java 在 Android 中將 RTF 轉換為 XLSX

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSX
otherformats: XLTM FODS DIF CSV EXCEL XLTX XLSM XLSB XLT XLS SXC XLAM ODS TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 應用程序中將 RTF 轉換為 XLSX" h2="在不使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 的情況下，通過 Java 在 Android 中將 RTF 導出為 XLSX" >}}

{{% blocks/products/pf/feature-page-summary %}}
通過使用 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)，您可以在您的 android 應用程序中集成 RTF 到 XLSX 轉換功能。首先，您可以使用功能豐富的文檔操作和轉換 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)將 RTF 轉換為 HTML。之後，通過使用 [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)，您可以將 HTML 轉換為 XLSX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API 將 RTF 轉換為 XLSX" %}}
1. 使用 [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument) 類打開 RTF 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) 將 RTF 轉換為 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載 HTML 文檔
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.)) 將文檔保存為 XLSX 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Cells for Android](https://rtfs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) 和 [Aspose.Words for Android via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository)在您的應用程序中。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 從 Android 中的 RTF 文檔中刪除未使用的信息" %}}
在將 RTF 轉換為 XLSX 之前，您可以通過 [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) 從 RTF 文檔中刪除未使用的信息。有時您可能需要刪除未使用或重複的信息以減少輸出文檔的大小和處理時間。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) 類允許您指定文檔清理的選項。要從文檔中刪除重複的樣式或只是未使用的樣式或列表，您可以使用 [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()) 方法。您可以使用 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 和 [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 屬性來檢測和刪除標記為“未使用”的樣式。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 將 XLSX 文件保存到 Android 中的流" %}}
將 RTF 轉換為 XLSX 後，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 使您能夠將文檔保存為流式傳輸。如果您需要將文件保存到 Stream，那麼您應該創建一個 FileOutputStream 對象，然後 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) 通過調用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 的 save 方法將文件保存到該 Stream 對象目的。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xltm/" name="RTF 至 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-fods/" name="RTF 至 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-dif/" name="RTF 至 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xlsx/" name="RTF 至 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-excel/" name="RTF 至 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xltx/" name="RTF 至 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xlsm/" name="RTF 至 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xlsb/" name="RTF 至 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xlt/" name="RTF 至 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xls/" name="RTF 至 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-sxc/" name="RTF 至 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-xlam/" name="RTF 至 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-ods/" name="RTF 至 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/rtf-to-tsv/" name="RTF 至 TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}