---
title: Android API 将 DOC 转换为 XLS
description: 在不使用 Microsoft Word 或 Microsoft Excel 的情况下，通过 Java 在 Android 中将 DOC 转换为 XLS

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLS
otherformats: DIF FODS XLTX EXCEL XLT XLSB ODS XLAM XLSM SXC XLTM CSV TSV XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Android 应用程序中将 DOC 转换为 XLS" h2="在不使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 的情况下，通过 Java 在 Android 中将 DOC 导出为 XLS" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)，您可以在您的 android 应用程序中集成 DOC 到 XLS 转换功能。首先，您可以使用功能丰富的文档操作和转换 API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)将 DOC 转换为 HTML。之后，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)，您可以将 HTML 转换为 XLS。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API 将 DOC 转换为 XLS" %}}
1. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类打开 DOC 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 将 DOC 转换为 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.)) 将文档保存为 XLS 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和通过 Java 安装 [Aspose.Cells for Android](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) 和 [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository)在您的应用程序中。

或者，您可以从 [下载](https://downloads.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 从 Android 中的 DOC 文档中删除未使用的信息" %}}
在将 DOC 转换为 XLS 之前，您可以通过 [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) 从 DOC 文档中删除未使用的信息。有时您可能需要删除未使用或重复的信息以减少输出文档的大小和处理时间。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) 类允许您指定文档清理的选项。要从文档中删除重复的样式或只是未使用的样式或列表，您可以使用 [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) 方法。您可以使用 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 和 [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 属性来检测和删除标记为“未使用”的样式。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 XLS 文件保存到 Android 中的流" %}}
将 DOC 转换为 XLS 后，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 使您能够将文档保存为流式传输。如果您需要将文件保存到 Stream，那么您应该创建一个 FileOutputStream 对象，然后 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) 通过调用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 的 save 方法将文件保存到该 Stream 对象目的。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-dif/" name="DOC 至 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-fods/" name="DOC 至 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xltx/" name="DOC 至 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-excel/" name="DOC 至 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xlt/" name="DOC 至 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xlsb/" name="DOC 至 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-ods/" name="DOC 至 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xlam/" name="DOC 至 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xlsm/" name="DOC 至 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-sxc/" name="DOC 至 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xltm/" name="DOC 至 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xls/" name="DOC 至 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-tsv/" name="DOC 至 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/doc-to-xlsx/" name="DOC 至 XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}