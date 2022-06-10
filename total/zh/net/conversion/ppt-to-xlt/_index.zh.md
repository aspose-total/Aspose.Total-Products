---
title: 通过 C# 将 PPT 转换为 XLT
description: 在 C# 中将 PPT 转换为 XLT，而不使用 Microsoft Excel 或 Powerpoint
url_ignore: /zh/net/conversion/ppt-to-xlt/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: XLT
otherformats: XLS XLAM SXC XLT XLTM ODS XLSM FODS TSV XLTX DIF MHTML EXCEL XLSX XLSB MARKDOWN DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 PPT 转换为 XLT" h2="用于 PPT 到 XLT 转换的 .NET API，无需使用 Microsoft<sup>&reg;</sup> Excel 或 PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中将 PPT 文件转换为 XLT，分两种简单的步骤。首先，通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPT 导出为 HTML。之后，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 电子表格编程 API，您可以将 HTML 转换为 XLT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何通过 C# 将 PPT 转换为 XLT" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类打开 PPT 文件
2. 使用 [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 方法将 PPT 导出为 HTML
3. 使用 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 类加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 方法将文档保存为 XLT
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://downloads.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将受保护的 PPT 转换为 XLT" %}}
在将 PPT 文件转换为 XLT 时，如果您的输入 PPT 文档受密码保护，则您无法在不解密文档的情况下将其转换为 XLT。当您的文档受密码保护时，这意味着它对演示文稿实施了某些限制。要取消限制，必须输入密码。受密码保护的演示文稿被视为锁定演示文稿。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 PPT 转换为带水印的 XLT" %}}
在将 PPT 文件转换为 XLT 时，您还可以在输出的 XLT 文件格式中添加水印。为了添加水印，您可以创建一个新的 Workbook 对象并打开转换后的 HTML 文档，通过其索引选择 Worksheet，创建一个 Shape 并使用其 AddTextEffect 函数。之后，您可以将 HTML 文档保存为带水印的 XLT。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-fods/" name="PPT 转 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xltm/" name="PPT 转 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xlt/" name="PPT 转 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xlam/" name="PPT 转 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-markdown/" name="PPT 转 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-excel/" name="PPT 转 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-mhtml/" name="PPT 转 MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xlsb/" name="PPT 转 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-ods/" name="PPT 转 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-sxc/" name="PPT 转 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xls/" name="PPT 转 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xltx/" name="PPT 转 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xlsx/" name="PPT 转 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-tsv/" name="PPT 转 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-dif/" name="PPT 转 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-xlsm/" name="PPT 转 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-doc/" name="PPT 转 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-docx/" name="PPT 转 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-docm/" name="PPT 转 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-dot/" name="PPT 转 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-dotm/" name="PPT 转 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-dotx/" name="PPT 转 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-odt/" name="PPT 转 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-ott/" name="PPT 转 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-rtf/" name="PPT 转 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-word/" name="PPT 转 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-wordml/" name="PPT 转 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-text/" name="PPT 转 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/ppt-to-flatopx/" name="PPT 转 FLA转PX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}