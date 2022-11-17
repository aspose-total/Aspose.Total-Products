---
title: 通过 Java 将 PPSM 导出到 Andorid 上的 DOTX
description: 在移动应用程序中将 PPSM 转换为 DOTX，无需安装任何软件

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOTX
otherformats: DOT FLATOPC DOCM DOTM DOC WORD TEXT DOCX ODT WORDML RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Andorid 上将 PPSM 渲染到 DOTX" h2="文件格式 API 可在 Android 应用程序中将 PPSM 转换为 DOTX，而不依赖于 Microsoft PowerPoint 或 Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 允许在 Android 应用程序中操作文件格式。通过使用包中提供的 API，您可以在您的应用程序中自动执行 PowerPoint PPSM 到 Word DOTX 的转换过程。
您可以分两步转换给定的文档。您可以使用 [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) 这是一个用于 Android 应用程序的 PowerPoint API 将 PPSM 呈现为 HTML。之后，通过使用文档处理 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以将 HTML 转换为 DOTX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android 中的 PPSM 到 DOTX 渲染" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类打开 PPSM 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 将 PPSM 转换为 HTML。ISaveOptions-) 方法并将 Html 设置为 SaveFormat
3. 使用 [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument) 类加载转换后的 HTML 文件
4. 使用[save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int))方法将文档保存为DOTX格式并设置Dotx保存格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和通过 Java 安装 [Aspose.Slides for Android](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 和 [Aspose.Words for Andorid 通过 Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)在你的应用程序。

或者，您可以从 [下载](https://downloads.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-dot/" name="PPSM 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-flatopc/" name="PPSM 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-dotxm/" name="PPSM 至 DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-dotm/" name="PPSM 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-dotx/" name="PPSM 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-word/" name="PPSM 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-text/" name="PPSM 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-dotxx/" name="PPSM 至 DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-odt/" name="PPSM 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-wordml/" name="PPSM 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-rtf/" name="PPSM 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/ppsm-to-ott/" name="PPSM 至 OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}