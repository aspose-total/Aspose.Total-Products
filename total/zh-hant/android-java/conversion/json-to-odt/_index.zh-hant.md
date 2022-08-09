---
title: 通過 Java 在 Android 中將 JSON 格式轉換為 ODT
description: 在不使用 Microsoft Word 的情況下在 Java 中將 JSON 解析為 ODT
url: /zh-hant/android-java/conversion/json-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODT
otherformats: EPUB PCL WORD FLATOPC OTT MOBI RTF PS DOC DOT DOTX CHM DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 應用程序中將 JSON 格式轉換為 ODT" h2="無需使用 Microsoft<sup>&reg;</sup> Word 在 Android 應用程序中將 JSON 解析為 ODT" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通過兩步過程在您的 Android 應用程序中將 JSON 轉換為 ODT。首先，通過使用強大的電子表格處理 API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以將 JSON 解析為 PDF。在第二步中，您可以使用 Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) 將 PDF 轉換為 ODT。這兩個 API 都屬於 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 產品系列。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通過 Java 在 Android 中將 JSON 格式轉換為 ODT" %}}
1. 創建一個新的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 對象並從文件中讀取有效的 JSON 數據
2. 使用 [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 類和 [Save](https://reference.aspose.com/) 將 JSON 文件導入工作表單元格 PDF
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 類加載 PDF 文檔
4. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 將文檔保存為 ODT 格式)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和在您的應用程序中安裝庫。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 中設置佈局並將 JSON 格式轉換為 ODT" %}}
此外，API 允許您在使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 將 JSON 解析為 ODT 時為 JSON 格式設置佈局選項。它允許您將 Array 處理為表格、忽略空值、忽略數組標題、忽略對象標題、將字符串轉換為數字或日期、設置日期和數字格式以及設置標題樣式。所有這些選項都允許您根據需要呈現數據。以下代碼片段向您展示瞭如何設置佈局選項。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 中將 JSON 格式轉換為帶水印的 ODT" %}}
使用 API，您還可以將 JSON 轉換為帶水印的 ODT。為了在您的 ODT 文檔中添加水印，您可以首先將 JSON 文件解析為 PDF 並為其添加水印。為了添加水印，使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 類加載新創建的 PDF 文件，創建 TextWatermarkOptions 的實例並設置它的屬性，調用 Watermark.setText 方法並傳遞水印文本和 TextWatermarkOptions 的對象。添加水印後，您可以將文檔保存到 ODT。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-epub/" name="JSON 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-pcl/" name="JSON 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-word/" name="JSON 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-flatopc/" name="JSON 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-ott/" name="JSON 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-mobi/" name="JSON 至 MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-rtf/" name="JSON 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-ps/" name="JSON 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-doc/" name="JSON 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-dot/" name="JSON 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-dotx/" name="JSON 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-odt/" name="JSON 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-docm/" name="JSON 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/json-to-wordml/" name="JSON 至 WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}