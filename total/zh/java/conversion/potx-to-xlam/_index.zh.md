---
title: 通过 Java 将 POTX 转换为 XLAM 格式
description: 通过 Java 将 POTX 转换为 XLAM 格式，而不使用 Microsoft Excel 或 PowerPoint
url_ignore: /zh/java/conversion/potx-to-xlam/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: XLAM
otherformats: ODS XLSM TSV XLSX FODS MARKDOWN XLSB DIF SXC XLT XLS EXCEL XLAM XLTX MHTML XLTM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 POTX 转换为 XLAM" h2="无需使用 Microsoft<sup>&reg;</sup> Excel 或 PowerPoint 即可将 POTX 导出为 XLAM 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 分两步将 POTX 文件转换为 XLAM。在第一步中，您可以使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) 将 POTX 导出为 HTML。其次，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 HTML 转换为 XLAM。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何通过 Java 将 POTX 转换为 XLAM" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类打开 POTX 文件
2. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) 将 POTX 转换为 HTML。 ISaveOptions-) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) 将文档保存为 XLAM 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 POTX 转换为 XLAM" %}}
使用 API，您还可以打开受密码保护的文档。如果您输入的 POTX 文档受密码保护，则您无法在不使用密码的情况下将其转换为 XLAM。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 POTX 文件转换为带水印的 XLAM" %}}
在将 POTX 文件转换为 XLAM 时，您还可以在输出的 XLAM 文件格式中添加水印。为了添加水印，创建一个新的工作簿来打开转换后的 HTML 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 HTML 文档保存为带水印的 XLAM。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-fods/" name="POTX 到 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xltm/" name="POTX 到 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xlt/" name="POTX 到 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xlam/" name="POTX 到 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-markdown/" name="POTX 到 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-excel/" name="POTX 到 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-mhtml/" name="POTX 到 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xlsb/" name="POTX 到 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-ods/" name="POTX 到 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-sxc/" name="POTX 到 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xls/" name="POTX 到 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xltx/" name="POTX 到 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xlsx/" name="POTX 到 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-tsv/" name="POTX 到 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-dif/" name="POTX 到 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-xlsm/" name="POTX 到 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-doc/" name="POTX 到 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-docx/" name="POTX 到 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-docm/" name="POTX 到 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-dot/" name="POTX 到 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-dotm/" name="POTX 到 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-dotx/" name="POTX 到 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-odt/" name="POTX 到 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-ott/" name="POTX 到 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-rtf/" name="POTX 到 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-word/" name="POTX 到 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-wordml/" name="POTX 到 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-text/" name="POTX 到 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/potx-to-flatopx/" name="POTX 到 FLA到PX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}