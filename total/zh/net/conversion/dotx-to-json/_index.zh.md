---
title: 通过 .NET 将 DOTX 转换为 JSON 格式
description: 不使用 Microsoft Excel 或 Adobe Reader 在 C# 中将 DOTX 转换为 JSON
url_ignore: /zh/net/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: XLT EXCEL ODS XLTM TSV XLAM SXC DIF XLS XLSB XLTX XLSX CSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 DOTX 转换为 JSON 格式" h2="通过 C# 将 DOTX 解析为 JSON，而不使用 Microsoft<sup>&reg;</sup> Word 或 Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中将 DOTX 转换为 JSON 格式。简单的步骤。首先，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOTX 导出为 HTML。之后，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 电子表格编程 API，您可以将 HTML 转换为 JSON。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 DOTX 转换为 JSON 格式" %}}
1.使用[Document](https://reference.aspose.com/words/net/aspose.words/Document)类打开DOTX文件
2. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4) 方法将 DOTX 转换为 HTML
3. 使用 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 类加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 方法将文档保存为 JSON 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将受保护的 DOTX 转换为 JSON 格式" %}}
使用 API，您还可以打开受密码保护的文档。如果您的输入 DOTX 文档受密码保护，则您无法在不使用密码的情况下将其转换为 JSON 格式。 API 允许您通过在 LoadOptions 对象中传递正确的密码来打开加密的文档。以下代码示例显示了如何尝试使用密码打开加密文档：  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 DOTX 转换为 Range 中的 JSON" %}}
在将 DOTX 转换为 JSON 时，您还可以将范围设置为输出 JSON 格式。为了设置范围，您可以使用 Workbook 类打开转换后的 HTML，获取包含数据的 Worksheet 的 CellsCollection，通过指定行和列索引从 CellsCollection 创建范围，并使用 Range 和 ExportRangeToJsonOptions 对象的引用调用 ExportRangeToJson 方法。最后，您可以通过 File.WriteAllText 方法将 JSON 数据保存到文件中。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-csv/" name="DOTX 转 CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xlam/" name="DOTX 转 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-sxc/" name="DOTX 转 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-tsv/" name="DOTX 转 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xlt/" name="DOTX 转 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-excel/" name="DOTX 转 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-dif/" name="DOTX 转 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xlsm/" name="DOTX 转 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xltm/" name="DOTX 转 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xlsx/" name="DOTX 转 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xlsb/" name="DOTX 转 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-fods/" name="DOTX 转 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-ods/" name="DOTX 转 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/dotx-to-xltx/" name="DOTX 转 XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}