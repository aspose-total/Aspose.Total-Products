---
title: 通过 Java 将 RTF 转换为 PPTX
description: 无需使用 Microsoft Word 或 PowerPoint 即可将 RTF 导出为 PPTX 的 Java API
url_ignore: /zh/java/conversion/rtf-to-pptx/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: PPTX
otherformats: POTX POT POTM POWERPOINT PPTM PPTX PPSM PPSX PPT PPS CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 RTF 转换为 PPTX" h2="通过在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 RTF 转换为 PPTX，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
通常，开发人员必须以编程方式将 RTF 文件转换为 PPTX。通过使用文件自动化 Java 库 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以通过几个简单的步骤来自动化渲染过程。您可以使用 [Aspose.Words for Java](https://products.aspose.com/words/java/) 加载 RTF 文件并将其转换为 HTML。之后，通过使用强大的 PowerPoint 操作 Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/)，您可以创建一个新的演示文稿，在其中写入 HTML 内容，并将其保存为 PPTX .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何通过 Java 将 RTF 转换为 PPTX" %}}
1. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类打开 RTF 文件
2. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将 RTF 文件转换为 HTML)) 方法
3.初始化一个新的[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)对象
5. 使用 BufferedReader 从 HTML 文件中提取内容并将内容写入您的演示文件
6. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) 方法将文档保存到 PPTX
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
对于 RTF 到 PPTX 文件的转换，您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 基于项目并在 pom.xml 中包含库。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-rtf-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="转换要求" %}}
该 API 还允许您将受密码保护的 RTF 文档转换为 PPTX。如果您输入的 RTF 文档受密码保护，则您无法在不使用密码的情况下将其转换为 PPTX 格式。为了打开加密文档，您可以在 LoadOptions 对象中设置正确的密码并将其传递给 Document 构造函数。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-rtf-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-ppsm/" name="RTF 到 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-pot/" name="RTF 到 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-powerpoint/" name="RTF 到 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-pptx/" name="RTF 到 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-potx/" name="RTF 到 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-pptm/" name="RTF 到 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-potm/" name="RTF 到 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-pps/" name="RTF 到 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-ppsx/" name="RTF 到 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-ppt/" name="RTF 到 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-csv/" name="RTF 到 CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-dif/" name="RTF 到 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-fods/" name="RTF 到 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-ods/" name="RTF 到 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-sxc/" name="RTF 到 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-tsv/" name="RTF 到 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xlam/" name="RTF 到 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xltm/" name="RTF 到 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-excel/" name="RTF 到 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xls/" name="RTF 到 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xlsb/" name="RTF 到 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xlsm/" name="RTF 到 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xlsx/" name="RTF 到 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xlt/" name="RTF 到 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xltm/" name="RTF 到 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/rtf-to-xltx/" name="RTF 到 XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}