---
title: 通過 Java 將 PPT 導出到 Andorid 上的 DOCM
description: 在移動應用程序中將 PPT 轉換為 DOCM，無需安裝任何軟件
url: /zh-hant/android-java/conversion/ppt-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCM
otherformats: DOCX RTF ODT DOTM TEXT OTT DOC FLATOPC DOTX WORD WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Andorid 上將 PPT 渲染到 DOCM" h2="文件格式 API 可在 Android 應用程序中將 PPT 轉換為 DOCM，而不依賴於 Microsoft PowerPoint 或 Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 允許在 Android 應用程序中操作文件格式。通過使用包中提供的 API，您可以在您的應用程序中自動執行 PowerPoint PPT 到 Word DOCM 的轉換過程。
您可以分兩步轉換給定的文檔。您可以使用 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) 這是一個用於 Android 應用程序的 PowerPoint API 將 PPT 呈現為 HTML。之後，通過使用文檔處理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以將 HTML 轉換為 DOCM。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android 中的 PPT 到 DOCM 渲染" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類打開 PPT 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 將 PPT 轉換為 HTML。ISaveOptions-) 方法並將 Html 設置為 SaveFormat
3. 使用 [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument) 類加載轉換後的 HTML 文件
4. 使用[save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,int))方法將文檔保存為DOCM格式並設置Docm保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Slides for Android](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 和 [Aspose.Words for Andorid 通過 Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)在你的應用程序。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docmument
Docmument docmument = new Docmument("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-docmx/" name="PPT 至 DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-rtf/" name="PPT 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-odt/" name="PPT 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-dotm/" name="PPT 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-text/" name="PPT 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-ott/" name="PPT 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-docm/" name="PPT 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-flatopc/" name="PPT 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-dotx/" name="PPT 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-word/" name="PPT 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-wordml/" name="PPT 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/ppt-to-dot/" name="PPT 至 DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}