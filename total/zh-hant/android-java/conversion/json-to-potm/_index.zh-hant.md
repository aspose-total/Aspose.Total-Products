---
title: 通過 Java 在 Android 中將 JSON 格式轉換為 POTM
description: 在不使用 Microsoft PowerPoint 的情況下在 Android 應用程序中將 JSON 解析為 POTM

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTM
otherformats: PPS PPTM ODP PPSX PPT PPSM POT POTX OTP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 中將 JSON 格式轉換為 POTM" h2="在不使用 Microsoft<sup>&reg;</sup> PowerPoint 的情況下在 Android 應用程序中將 JSON 格式解析為 POTM" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以分兩步將 Android 應用程序中的 JSON 格式轉換為 POTM。首先，通過使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以將 JSON 解析為 PPTX。之後，通過使用 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)，您可以將 PPTX 轉換為 POTM。這兩個 API 都屬於 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Android 中將 JSON 格式轉換為 POTM" %}}
1. 建[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)對象並打開JSON文件
2. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 將 JSON 保存為 PPTX ) 方法
3. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類加載 PPTX 文檔
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法將文檔保存為 POTM 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和在您的應用程序中安裝庫。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 應用程序中設置佈局並將 JSON 格式轉換為 POTM" %}}
此外，該 API 允許您使用指定的佈局選項將 JSON 解析為 POTM。為了指定佈局選項，您可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 類。它允許您將數組作為表格處理、忽略空值、忽略數組標題、忽略對象標題、將字符串轉換為數字或日期、設置日期和數字格式以及設置標題樣式。所有這些選項都允許您根據需要呈現數據。以下代碼片段向您展示瞭如何設置佈局選項。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 中將 JSON 格式轉換為帶水印的 POTM" %}}
使用 API，您還可以將 JSON 轉換為帶水印的 POTM。為了給你的 POTM 文檔添加水印，你可以先將 JSON 解析為 PPTX 並為其添加水印。為了添加水印，使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類加載新創建的 PPTX 文件，遍歷所有幻燈片，添加文本使用 addTextFrame，設置所有相關選項，如顏色、填充類型等，並可以將文檔保存到 POTM。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}