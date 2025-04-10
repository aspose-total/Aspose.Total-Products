---
title: 通过 C# API 将 CGM 转换为 TXT
description: 无需使用 Microsoft Excel 或 Adobe Reader 即可将 CGM 文件转换为 TXT 的 C# API
url_ignore: /zh/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 CGM 渲染为 TXT 的 C# API" h2="在不使用 Microsoft<sup>&reg;</sup> Excel 或 Adobe<sup>&reg;</sup> Acrobat Reader 的情况下，通过 C# 将 CGM 文件导出为 TXT" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中轻松地将 CGM 文件转换为 TXT。首先，通过使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 CGM 导出到 XLSX。之后，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 电子表格编程 API，您可以将 XLSX 转换为 TXT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 CGM 转换为 TXT" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开CGM文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将CGM转换为XLSX
3. 使用 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 类加载 XLSX 文档
4. 使用 [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 方法将文档保存为 TXT 格式，并将 `Txt` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将受保护的 CGM 转换为 TXT" %}}
如果您的 CGM 文档受密码保护，则您无法在没有密码的情况下将其转换为 TXT。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，您可以初始化 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 类的新实例，并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 CGM 文件转换为带水印的 TXT" %}}
在将 CGM 文件转换为 TXT 时，您还可以在输出的 TXT 文件格式中添加水印。为了添加水印，您可以创建一个新的 Workbook 对象并打开转换后的 XLSX 文档，通过其索引选择 Worksheet，创建一个 Shape 并使用其 AddTextEffect 函数。之后，您可以将 XLSX 文档保存为带水印的 TXT。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 CGM 文件转换为 TXT：用例" %}}
CGM（计算机图形元文件）用于存储向量图形信息，是制作静态图形和插图的理想选择。然而，在处理动态数据时，文本编辑器如Notepad成为基本文本操作和文档编写的必要工具。

将CGM文件转换为纯文本格式是解锁您文本编辑功能全力以赴的关键。这一转换使您能够：

**用途：**

*   **数据文档编写**：将CGM文件转换为人类可读的文档，使图形信息更易理解和分享。
*   **文本操作**：使用Notepad编辑并处理从CGM文件中提取的纯文本数据，以适合基本文本编辑任务。
*   **ASCII艺术创作**：将CGM文件转换为ASCII艺术，创建简单的基于文本的图形表示，以满足艺术或装饰目的。
*   **其他工具的数据导入**：通过转换为纯文本格式，将图形数据导入其他文本编辑器或文字处理软件，从而扩展您的文本操作能力。
*   **基础报告和调试**：将CGM文件转换为基本报表或调试日志，以帮助识别开发过程中出现的错误和问题。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}