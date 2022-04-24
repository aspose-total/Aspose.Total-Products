---
title: 通过 Java 将 DOCX 转换为 JSON 格式
description: 通过 Java 将 DOCX 转换为 JSON 格式，而不使用 Microsoft Word 或 Microsoft Excel
url: /zh/java/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 DOCX 转换为 JSON 格式" h2="无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 即可将 DOCX 转换为 JSON 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将 DOCX 转换为 JSON 格式是一个简单的两步过程。通过使用功能丰富的文档操作和转换 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 DOCX 导出为 HTML。之后，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 HTML 转换为 JSON。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 DOCX 转换为 JSON 格式" %}}
1. 使用 [Docxument](https://apireference.aspose.com/words/java/com.aspose.words/Docxument) 类打开 DOCX 文件
2. 使用 [Save](https://apireference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) 将 DOCX 转换为 HTML ） 方法
3. 使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.) 将文档保存为 JSON 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 DOCX 转换为 JSON 格式" %}}
使用 API，您还可以打开受密码保护的文档。如果您的输入 DOCX 文档受密码保护，则您无法在不使用密码的情况下将其转换为 JSON 格式。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。以下代码示例显示了如何尝试使用密码打开加密文档：  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 DOCX 转换为 Range 中的 JSON" %}}
在将 DOCX 转换为 JSON 时，您还可以将范围设置为输出 JSON 格式。为了设置范围，您可以使用 Workbook 类打开转换后的 HTML，使用 Cells.createRange 方法创建要导出的数据范围，使用 Range 和 ExportRangeToJsonOptions 的引用调用 JsonUtility.exportRangeToJson 方法并将字符串 JSON 数据写入文件通过BufferedWriter.write 方法。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xlam/" name="DOCX 到 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xlt/" name="DOCX 到 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-csv/" name="DOCX 到 CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xlsx/" name="DOCX 到 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-fods/" name="DOCX 到 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xltm/" name="DOCX 到 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xlsm/" name="DOCX 到 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xltx/" name="DOCX 到 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-ods/" name="DOCX 到 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-xlsb/" name="DOCX 到 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-excel/" name="DOCX 到 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-sxc/" name="DOCX 到 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-tsv/" name="DOCX 到 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/docx-to-dif/" name="DOCX 到 DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}