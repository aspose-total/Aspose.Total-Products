---
title: Java API 将 DOTM 转换为 XLTX
description: 通过 Java 将 DOTM 转换为 XLTX，而不使用 Microsoft Word 或 Microsoft Excel
url: /zh/java/conversion/dotm-to-xltx/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: XLTX
otherformats: TSV XLAM SXC XLTX EXCEL ODS FODS XLSM XLTX XLS XLSX DIF XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 DOTM 转换为 XLTX" h2="无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 即可将 DOTM 转换为 XLTX 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将 DOTM 转换为 XLTX 是一个简单的两步过程。通过使用功能丰富的文档操作和转换 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOTM 导出为 HTML。之后，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 HTML 转换为 XLTX。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 DOTM 转换为 XLTX 的 C++ API" %}}
1. 使用 [Dotmument](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument) 类打开 DOTM 文件
2. 使用 [Save](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) 将 DOTM 转换为 HTML ） 方法
3. 使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) 将文档保存为 XLTX 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 从 DOTM 文档中删除未使用的信息" %}}
在将 DOTM 转换为 XLTX 之前，您可以通过 [Aspose.Words for Java](https://products.aspose.com/words/java/) 从 DOTM 文档中删除未使用的信息。有时您可能需要删除未使用或重复的信息以减少输出文档的大小和处理时间。 [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) 类允许您指定文档清理的选项。要从文档中删除重复的样式或仅未使用的样式或列表，您可以使用 [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup()) 方法。您可以使用 [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 和 [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 属性来检测和删除标记为“未使用”的样式。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}(https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions))
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 XLTX 文件保存到流" %}}
将 DOTM 转换为 XLTX 后，[Aspose.Cells for Java](https://products.aspose.com/cells/java/) 使您能够将文档保存为流式传输。如果您需要将文件保存到 Stream 那么您应该创建一个 FileOutputStream 对象，然后 [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) 通过调用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 的 save 方法将文件保存到该 Stream 对象目的。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xlsm/" name="DOTM 到 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xlt/" name="DOTM 到 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-ods/" name="DOTM 到 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-tsv/" name="DOTM 到 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xls/" name="DOTM 到 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xlsb/" name="DOTM 到 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-fods/" name="DOTM 到 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-dif/" name="DOTM 到 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xltx/" name="DOTM 到 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xlam/" name="DOTM 到 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xlsx/" name="DOTM 到 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-xltm/" name="DOTM 到 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-sxc/" name="DOTM 到 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotm-to-excel/" name="DOTM 到 EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}