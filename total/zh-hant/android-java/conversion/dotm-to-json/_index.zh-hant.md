---
title: 通過 Java 在 Android 中將 DOTM 轉換為 JSON 格式
description: 在不使用 Microsoft Word 或 Excel 的情況下，通過 Java 在 Android 中將 DOTM 解析為 JSON 格式

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 中將 DOTM 轉換為 JSON 格式" h2="設計 Android 應用程序以將 DOTM 導出為 JSON，而無需使用 Microsoft<sup>&reg;</sup> Word 或 Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通過 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 在您的 Android 應用程序中將 DOTM 轉換為 JSON 格式。通過使用文檔操作和轉換 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以將 DOTM 導出為 HTML。之後，通過使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以將 HTML 轉換為 JSON。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Android 中將 DOTM 轉換為 JSON 格式" %}}
1. 使用 [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument) 類打開 DOTM 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) 將 DOTM 轉換為 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載 HTML 文檔
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.)) 將文檔保存為 JSON 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和在您的應用程序中安裝庫。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 中將受保護的 DOTM 轉換為 JSON 格式" %}}
使用 API，您還可以打開受密碼保護的文檔。如果您的輸入 DOTM 文檔受密碼保護，則您無法在不使用密碼的情況下將其轉換為 JSON 格式。 API 允許您通過在 LoadOptions 對像中傳遞正確的密碼來打開加密的文檔。以下代碼示例顯示如何使用密碼打開加密文檔。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過Java在Android中將DOTM轉換為範圍內的JSON" %}}
在將 DOTM 轉換為 JSON 時，您還可以將範圍設置為輸出 JSON 格式。為了設置範圍，您可以使用 Workbook 類打開轉換後的 HTML，使用 Cells.createRange 方法創建要導出的數據范圍，使用 Range 和 ExportRangeToJsonOptions 的引用調用 JsonUtility.exportRangeToJson 方法並將字符串 JSON 數據寫入文件通過BufferedWriter.write 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}