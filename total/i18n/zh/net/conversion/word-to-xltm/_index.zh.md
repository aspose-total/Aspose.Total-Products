---
title: .NET API 将 WORD 转换为 XLTM
description: 无需使用 Microsoft Excel 或 Adobe Reader 即可将 WORD 转换为 XLTM 的 C# API
url: /zh/net/conversion/word-to-xltm/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: XLTM
otherformats: FODS DIF SXC EXCEL XLSM XLSX XLTM XLAM TSV ODS XLT XLTX XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 WORD 转换为 XLTM 的 C# API" h2="通过 C# 将 WORD 导出为 XLTM，无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中包含 WORD 到 XLTM 的转换功能两个简单的步骤。首先，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 WORD 导出为 HTML。之后，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 电子表格编程 API，您可以将 HTML 转换为 XLTM。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 WORD 转换为 XLTM" %}}
1.使用[Wordument](https://apireference.aspose.com/words/net/aspose.words/wordument)类打开WORD文件
2. 使用 [Save](https://apireference.aspose.com/words/net/aspose.words.wordument/save/methods/4) 方法将 WORD 转换为 HTML
3. 使用 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 类加载 HTML 文档
4. 使用 [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 方法将文档保存为 XLTM 格式，并将 `XLTM` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://downloads.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 从 Stream 加载 WORD 文档" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) 还允许您通过流加载 WORD 文档。要从流中打开文档，只需将包含文档的流对象传递给 [Wordument](https://apireference.aspose.com/words/net/aspose.words/wordument) 构造函数。以下代码示例显示了如何从流中打开文档：  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 在 XLTM 文件中添加自定义属性" %}}
在将 WORD 转换为 XLTM 时，[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 允许您在 XLTM 文档中添加自定义属性。为了添加自定义属性，您可以对 [CustomWordumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordumentpropertycollection）类。 Add 方法将属性添加到 Excel 文件，并以 [Aspose.Cells.Properties.WordumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties) 的形式返回新文档属性的引用/wordumentproperty) 对象。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-dif/" name="WORD 转 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xlsb/" name="WORD 转 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-tsv/" name="WORD 转 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-fods/" name="WORD 转 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xlt/" name="WORD 转 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-excel/" name="WORD 转 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xlsx/" name="WORD 转 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-ods/" name="WORD 转 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-sxc/" name="WORD 转 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xlam/" name="WORD 转 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xltm/" name="WORD 转 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xlsm/" name="WORD 转 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xls/" name="WORD 转 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/word-to-xltx/" name="WORD 转 XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}