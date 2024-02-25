---
title: 通过 Java 在 Android 中将 JSON 格式转换为 MOBI
description: 在不使用 Microsoft Word 的情况下在 Java 中将 JSON 解析为 MOBI

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: RTF ODT FLATOPC OTT WORD DOT EPUB DOTX PCL DOCM DOC CHM PS WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 应用程序中将 JSON 格式转换为 MOBI" h2="无需使用 Microsoft<sup>&reg;</sup> Word 在 Android 应用程序中将 JSON 解析为 MOBI" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过两步过程在您的 Android 应用程序中将 JSON 转换为 MOBI。首先，通过使用强大的电子表格处理 API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以将 JSON 解析为 PDF。在第二步中，您可以使用 Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) 将 PDF 转换为 MOBI。这两个 API 都属于 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 产品系列。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 在 Android 中将 JSON 格式转换为 MOBI" %}}
1. 创建一个新的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 类和 [Save](https://reference.aspose.com/) 将 JSON 文件导入工作表单元格 PDF
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 PDF 文档
4. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 将文档保存为 MOBI 格式)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和在您的应用程序中安装库。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中设置布局并将 JSON 格式转换为 MOBI" %}}
此外，API 允许您在使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 将 JSON 解析为 MOBI 时为 JSON 格式设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中将 JSON 格式转换为带水印的 MOBI" %}}
使用 API，您还可以将 JSON 转换为带水印的 MOBI。为了给您的 MOBI 文档添加水印，您可以首先将 JSON 文件解析为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载新创建的 PDF 文件，创建 TextWatermarkOptions 的实例并设置它的属性，调用 Watermark.setText 方法并传递水印文本和 TextWatermarkOptions 的对象。添加水印后，您可以将文档保存到 MOBI。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}