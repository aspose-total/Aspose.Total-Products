---
title: Android API 將 DOTM 轉換為 XLTX
description: 在不使用 Microsoft Word 或 Microsoft Excel 的情況下，通過 Java 在 Android 中將 DOTM 轉換為 XLTX

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLTX
otherformats: TSV FODS SXC ODS DIF XLS XLT XLSB XLSM EXCEL XLTM CSV XLAM XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 應用程序中將 DOTM 轉換為 XLTX" h2="在不使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 的情況下，通過 Java 在 Android 中將 DOTM 導出為 XLTX" >}}

{{% blocks/products/pf/feature-page-summary %}}
通過使用 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)，您可以在您的 android 應用程序中集成 DOTM 到 XLTX 轉換功能。首先，您可以使用功能豐富的文檔操作和轉換 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)將 DOTM 轉換為 HTML。之後，通過使用 [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)，您可以將 HTML 轉換為 XLTX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API 將 DOTM 轉換為 XLTX" %}}
1. 使用 [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument) 類打開 DOTM 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) 將 DOTM 轉換為 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載 HTML 文檔
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.)) 將文檔保存為 XLTX 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Cells for Android](https://dotms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) 和 [Aspose.Words for Android via Java](https://dotms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository)在您的應用程序中。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免費的 DOTM 到 XLTX 在線轉換器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xltx&from=dotm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="通過 Java 從 Android 中的 DOTM 文檔中刪除未使用的信息" %}}
在將 DOTM 轉換為 XLTX 之前，您可以通過 [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) 從 DOTM 文檔中刪除未使用的信息。有時您可能需要刪除未使用或重複的信息以減少輸出文檔的大小和處理時間。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) 類允許您指定文檔清理的選項。要從文檔中刪除重複的樣式或只是未使用的樣式或列表，您可以使用 [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup()) 方法。您可以使用 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 和 [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 屬性來檢測和刪除標記為“未使用”的樣式。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotmument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 將 XLTX 文件保存到 Android 中的流" %}}
將 DOTM 轉換為 XLTX 後，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 使您能夠將文檔保存為流式傳輸。如果您需要將文件保存到 Stream，那麼您應該創建一個 FileOutputStream 對象，然後 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) 通過調用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 的 save 方法將文件保存到該 Stream 對象目的。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-tsv/" name="DOTM 至 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-fods/" name="DOTM 至 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-sxc/" name="DOTM 至 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-ods/" name="DOTM 至 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-dif/" name="DOTM 至 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xls/" name="DOTM 至 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xlt/" name="DOTM 至 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xlsb/" name="DOTM 至 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xlsm/" name="DOTM 至 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-excel/" name="DOTM 至 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xltm/" name="DOTM 至 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xltx/" name="DOTM 至 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xlam/" name="DOTM 至 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/dotm-to-xlsx/" name="DOTM 至 XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}