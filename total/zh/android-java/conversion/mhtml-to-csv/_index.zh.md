---
title: 通过 Java 在 Android 中将 MHTML 转换为 CSV
description: 在不使用 Microsoft Excel 或 Adobe Reader 的情况下，通过 Java API 在 Android 中将 MHTML 渲染为 CSV

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: CSV
otherformats: TXT XLTM XLAM ODS XLTX FODS XLSB XLT MD XLSM TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 中将 MHTML 渲染为 CSV" h2="在 Android 应用程序中将 MHTML 转换为 CSV，无需 Microsoft<sup>&reg;</sup> Excel 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过两步过程在您的 android 应用程序中集成 MHTML 到 CSV 转换功能。首先，通过使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)，您可以将 MHTML 转换为 XLSX。其次，您可以使用强大的电子表格处理 API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)将 XLSX 转换为 CSV。这两个 API 都属于 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 产品系列。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 MHTML 渲染为 CSV 的 Android API" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开MHTML文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 将 MHTML 转换为 XLSX ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook) 将文档保存为 CSV 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和安装 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/) 在您的应用程序中。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中获取 MHTML 文件的 XMP 元数据" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 允许您访问 MHTML 文件的 XMP 元数据。为了获取元数据，创建一个 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 对象并打开输入 MHTML 文件并使用 [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) 属性来获取元数据。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 保护 Android 中的 CSV 文档" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 支持根据您的需要保护您的 CSV 文件。为了保护您的文档，您可以使用 [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) 方法类。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-csv.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}