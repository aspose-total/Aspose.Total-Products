---
title: 通过 Java 在 Android 中将 PPT 转换为 JSON
description: 在不使用 Microsoft Excel 或 PowerPoint 的情况下，通过 Java 在 Android 中将 PPT 转换为 JSON

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 中将 PPT 转换为 JSON" h2="无需使用 Microsoft<sup>&reg;</sup> Excel 或 PowerPoint 在 Android 应用程序中将 PPT 文件导出为 JSON" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 分两步在 Android 应用程序中轻松地将 PPT 文件转换为 JSON。第一步，您可以使用 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) 将 PPT 文件导出为 HTML。其次，通过使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以将 HTML 转换为 JSON。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Android 中将 PPT 转换为 JSON" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类打开 PPT 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 将 PPT 转换为 HTML。ISaveOptions-) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/) 将文档保存为 JSON 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
为了将 PPT 转换为 JSON，您可以直接从 [Maven](https://releases.aspose.com/total/java/)并在您的应用程序中安装库。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 中通过 Java 将 Protected PPT 转换为 JSON" %}}
使用 API，您还可以打开受密码保护的文档。如果您输入的 PPT 文档受密码保护，则您无法在不使用密码的情况下将其转换为 JSON。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。以下代码示例显示了如何尝试使用密码打开加密文档：
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 中将 PPT 文件转换为带有水印的 JSON" %}}
在将 PPT 文件转换为 JSON 时，您还可以在输出的 JSON 文件格式中添加水印。为了添加水印，创建一个新的工作簿来打开转换后的 HTML 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 HTML 文档保存为带水印的 JSON。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}