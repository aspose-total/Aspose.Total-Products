---
title: 通過 Java 將 PPTM 導出到 Andorid 上的 WORDML
description: 在移動應用程序中將 PPTM 轉換為 WORDML，無需安裝任何軟件

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: WORDML
otherformats: DOTM OTT RTF DOCX DOC DOCM DOTX TEXT DOT FLATOPC ODT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Andorid 上將 PPTM 渲染到 WORDML" h2="文件格式 API 可在 Android 應用程序中將 PPTM 轉換為 WORDML，而不依賴於 Microsoft PowerPoint 或 Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 允許在 Android 應用程序中操作文件格式。通過使用包中提供的 API，您可以在您的應用程序中自動執行 PowerPoint PPTM 到 Word WORDML 的轉換過程。
您可以分兩步轉換給定的文檔。您可以使用 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) 這是一個用於 Android 應用程序的 PowerPoint API 將 PPTM 呈現為 HTML。之後，通過使用文檔處理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以將 HTML 轉換為 WORDML。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android 中的 PPTM 到 WORDML 渲染" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類打開 PPTM 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 將 PPTM 轉換為 HTML。ISaveOptions-) 方法並將 Html 設置為 SaveFormat
3. 使用 [Wordmlument](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument) 類加載轉換後的 HTML 文件
4. 使用[save](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument#save(java.lang.String,int))方法將文檔保存為WORDML格式並設置Wordml保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Slides for Android](https://wordmls.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 和 [Aspose.Words for Andorid 通過 Java](https://wordmls.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)在你的應用程序。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("input.pptm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("htmlOutput.html");
// save wordmlument in WORDML format
wordmlument.save("output.wordml",SaveFormat.WordML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-dotm/" name="PPTM 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-ott/" name="PPTM 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-rtf/" name="PPTM 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-wordmlx/" name="PPTM 至 WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-wordml/" name="PPTM 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-wordmlm/" name="PPTM 至 WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-dotx/" name="PPTM 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-text/" name="PPTM 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-dot/" name="PPTM 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-flatopc/" name="PPTM 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-odt/" name="PPTM 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/pptm-to-word/" name="PPTM 至 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}