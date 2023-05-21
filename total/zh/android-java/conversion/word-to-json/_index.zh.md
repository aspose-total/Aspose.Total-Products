---
title: 通过 Java 在 Android 中将 WORD 转换为 JSON 格式
description: 在不使用 Microsoft Word 或 Excel 的情况下，通过 Java 在 Android 中将 WORD 解析为 JSON 格式

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 中将 WORD 转换为 JSON 格式" h2="设计 Android 应用程序以将 WORD 导出为 JSON，而无需使用 Microsoft<sup>&reg;</sup> Word 或 Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 在您的 Android 应用程序中将 WORD 转换为 JSON 格式。通过使用文档操作和转换 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)，您可以将 WORD 导出为 HTML。之后，通过使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)，您可以将 HTML 转换为 JSON。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Android 中将 WORD 转换为 JSON 格式" %}}
1. 使用 [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument) 类打开 WORD 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) 将 WORD 转换为 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.)) 将文档保存为 JSON 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和在您的应用程序中安装库。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中将受保护的 WORD 转换为 JSON 格式" %}}
使用 API，您还可以打开受密码保护的文档。如果您的输入 WORD 文档受密码保护，则您无法在不使用密码的情况下将其转换为 JSON 格式。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。以下代码示例显示如何使用密码打开加密文档。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过Java在Android中将WORD转换为范围内的JSON" %}}
在将 WORD 转换为 JSON 时，您还可以将范围设置为输出 JSON 格式。为了设置范围，您可以使用 Workbook 类打开转换后的 HTML，使用 Cells.createRange 方法创建要导出的数据范围，使用 Range 和 ExportRangeToJsonOptions 的引用调用 JsonUtility.exportRangeToJson 方法并将字符串 JSON 数据写入文件通过BufferedWriter.write 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}