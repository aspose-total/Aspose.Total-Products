---
title: 通过 Java 在 Android 中将 JSON 格式转换为 PPS
description: 在不使用 Microsoft PowerPoint 的情况下在 Android 应用程序中将 JSON 解析为 PPS

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPS
otherformats: ODP PPSM POWERPOINT POT OTP POTX PPTM PPT PPSX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 中将 JSON 格式转换为 PPS" h2="在不使用 Microsoft<sup>&reg;</sup> PowerPoint 的情况下在 Android 应用程序中将 JSON 格式解析为 PPS" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以分两步将 Android 应用程序中的 JSON 格式转换为 PPS。首先，通过使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以将 JSON 解析为 PPTX。之后，通过使用 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)，您可以将 PPTX 转换为 PPS。这两个 API 都属于 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Android 中将 JSON 格式转换为 PPS" %}}
1. 建[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)对象并打开JSON文件
2. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 将 JSON 保存为 PPTX ) 方法
3. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类加载 PPTX 文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 PPS 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和在您的应用程序中安装库。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 应用程序中设置布局并将 JSON 格式转换为 PPS" %}}
此外，该 API 允许您使用指定的布局选项将 JSON 解析为 PPS。为了指定布局选项，您可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 类。它允许您将数组作为表格处理、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中将 JSON 格式转换为带水印的 PPS" %}}
使用 API，您还可以将 JSON 转换为带水印的 PPS。为了给你的 PPS 文档添加水印，你可以先将 JSON 解析为 PPTX 并为其添加水印。为了添加水印，使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类加载新创建的 PPTX 文件，遍历所有幻灯片，添加文本使用 addTextFrame，设置所有相关选项，如颜色、填充类型等，并可以将文档保存到 PPS。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}