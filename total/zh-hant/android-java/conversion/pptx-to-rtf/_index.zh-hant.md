---
title: 通過 Java 將 PPTX 導出到 Andorid 上的 RTF 或使用免費的在線轉換器
description: 在移動應用程序中將 PPTX 轉換為 RTF，無需安裝任何軟件 或在線。在集成代碼之前快速測試免費的 CSV 到 DOC 在線轉換器。

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: RTF
otherformats: FLATOPC DOTX WORD TEXT DOCM ODT OTT DOCX WORDML DOC DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Andorid 上將 PPTX 渲染到 RTF 或在線應用程序" h2="文件格式 API 可在 Android 應用程序中將 PPTX 轉換為 RTF，而不依賴於 Microsoft PowerPoint 或 Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 允許在 Android 應用程序中操作文件格式。通過使用包中提供的 API，您可以在您的應用程序中自動執行 PowerPoint PPTX 到 Word RTF 的轉換過程。
您可以分兩步轉換給定的文檔。您可以使用 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) 這是一個用於 Android 應用程序的 PowerPoint API 將 PPTX 呈現為 HTML。之後，通過使用文檔處理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以將 HTML 轉換為 RTF。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android 中的 PPTX 到 RTF 渲染" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類打開 PPTX 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 將 PPTX 轉換為 HTML。ISaveOptions-) 方法並將 Html 設置為 SaveFormat
3. 使用 [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument) 類加載轉換後的 HTML 文件
4. 使用[save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int))方法將文檔保存為RTF格式並設置Rtf保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Slides for Android](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 和 [Aspose.Words for Andorid 通過 Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)在你的應用程序。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免費的 PPTX 到 RTF 在線轉換器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=pptx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}