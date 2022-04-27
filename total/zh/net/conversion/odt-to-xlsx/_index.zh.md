---
title: .NET API 将 ODT 转换为 XLSX
description: 无需使用 Microsoft Excel 或 Adobe Reader 即可将 ODT 转换为 XLSX 的 C# API
url: /zh/net/conversion/odt-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: XLSX
otherformats: XLSB XLAM FODS XLT XLS ODS DIF XLTX SXC XLSX XLSM TSV XLTM EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 ODT 转换为 XLSX 的 C# API" h2="通过 C# 将 ODT 导出为 XLSX，无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中包含 ODT 到 XLSX 的转换功能两个简单的步骤。首先，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 ODT 导出为 HTML。之后，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 电子表格编程 API，您可以将 HTML 转换为 XLSX。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 ODT 转换为 XLSX" %}}
1.使用[Odtument](https://apireference.aspose.com/words/net/aspose.words/odtument)类打开ODT文件
2. 使用 [Save](https://apireference.aspose.com/words/net/aspose.words.odtument/save/methods/4) 方法将 ODT 转换为 HTML
3. 使用 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 类加载 HTML 文档
4. 使用 [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 方法将文档保存为 XLSX 格式，并将 `XLSX` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://downloads.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 从 Stream 加载 ODT 文档" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) 还允许您通过流加载 ODT 文档。要从流中打开文档，只需将包含文档的流对象传递给 [Odtument](https://apireference.aspose.com/words/net/aspose.words/odtument) 构造函数。以下代码示例显示了如何从流中打开文档：  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(https
{{% blocks/products/pf/feature-page-section  h2="通过 C# 在 XLSX 文件中添加自定义属性" %}}
在将 ODT 转换为 XLSX 时，[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 允许您在 XLSX 文档中添加自定义属性。为了添加自定义属性，您可以对 [CustomOdtumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customodtumentpropertycollection）类。 Add 方法将属性添加到 Excel 文件，并以 [Aspose.Cells.Properties.OdtumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties) 的形式返回新文档属性的引用/odtumentproperty) 对象。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-dif/" name="ODT 转 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xlsb/" name="ODT 转 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-tsv/" name="ODT 转 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-fods/" name="ODT 转 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xlt/" name="ODT 转 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-excel/" name="ODT 转 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xlsx/" name="ODT 转 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-ods/" name="ODT 转 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-sxc/" name="ODT 转 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xlam/" name="ODT 转 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xltm/" name="ODT 转 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xlsm/" name="ODT 转 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xls/" name="ODT 转 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/odt-to-xltx/" name="ODT 转 XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}