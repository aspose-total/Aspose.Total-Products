---
title: 通过 .NET 将 JSON 格式转换为 RTF
description: 在 C# 中将 JSON 解析为 RTF，而不使用 Microsoft Word
url_ignore: /zh/net/conversion/json-to-rtf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: RTF
otherformats: DOCM ODT DOTX DOC EPUB WORD DOT OTT FLATOPC PCL MOBI PS RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 JSON 格式转换为 RTF" h2="无需使用 Microsoft<sup>&reg;</sup> Word 即可将 JSON 解析为 RTF 的 C# API" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中以两个简单的方式将 JSON 解析为 RTF脚步。首先，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)，您可以将 JSON 导出为 PDF。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 PDF 转换为 RTF。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 JSON 格式转换为 RTF" %}}
1. 创建一个新的 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) 类和 [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 将 JSON 文件导入工作表 以 PDF 格式
3. 用[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载PDF文档
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3) 方法将文档保存为 RTF 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 设置布局并将 JSON 格式转换为 RTF" %}}
在将 JSON 解析为 RTF 时，您还可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) 为 JSON 设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="将 JSON 格式解析为带水印的 RTF" %}}
使用 API，您还可以将 JSON 转换为带水印的 RTF。为了给您的 RTF 文档添加水印，您可以首先将 JSON 文件解析为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载新创建的 PDF 文件，创建 TextWatermarkOptions 的实例并设置其属性, 调用 Watermark.SetText 方法并传递水印文本和 TextWatermarkOptions 的对象。添加水印后，您可以将文档保存到 RTF。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}