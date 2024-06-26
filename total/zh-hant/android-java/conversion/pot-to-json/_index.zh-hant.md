---
title: 通過 Java 在 Android 中將 POT 轉換為 JSON
description: 在不使用 Microsoft Excel 或 PowerPoint 的情況下，通過 Java 在 Android 中將 POT 轉換為 JSON

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 中將 POT 轉換為 JSON" h2="無需使用 Microsoft<sup>&reg;</sup> Excel 或 PowerPoint 在 Android 應用程序中將 POT 文件導出為 JSON" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通過 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 分兩步在 Android 應用程序中輕鬆地將 POT 文件轉換為 JSON。第一步，您可以使用 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) 將 POT 文件導出為 HTML。其次，通過使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以將 HTML 轉換為 JSON。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Android 中將 POT 轉換為 JSON" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類打開 POT 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 將 POT 轉換為 HTML。ISaveOptions-) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載 HTML 文檔
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/) 將文檔保存為 JSON 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
為了將 POT 轉換為 JSON，您可以直接從 [Maven](https://releases.aspose.com/total/java/)並在您的應用程序中安裝庫。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 中通過 Java 將 Protected POT 轉換為 JSON" %}}
使用 API，您還可以打開受密碼保護的文檔。如果您輸入的 POT 文檔受密碼保護，則您無法在不使用密碼的情況下將其轉換為 JSON。 API 允許您通過在 LoadOptions 對像中傳遞正確的密碼來打開加密的文檔。以下代碼示例顯示瞭如何嘗試使用密碼打開加密文檔：
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 中將 POT 文件轉換為帶有水印的 JSON" %}}
在將 POT 文件轉換為 JSON 時，您還可以在輸出的 JSON 文件格式中添加水印。為了添加水印，創建一個新的工作簿來打開轉換後的 HTML 文件。通過其索引選擇 Worksheet，創建一個 Shape 並使用其 addTextEffect 函數，設置顏色、透明度等。之後，您可以將 HTML 文檔保存為帶水印的 JSON。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}