---
title: 通过 C# API 将 CGM 转换为 TSV
description: 无需使用 Microsoft Excel 或 Adobe Reader 即可将 CGM 文件转换为 TSV 的 C# API
url_ignore: /zh/net/conversion/cgm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TSV
otherformats: TSV FODS XLSM EXCEL TXT SXC XLAM ODS DIF XLSB XLT MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 CGM 渲染为 TSV 的 C# API" h2="在不使用 Microsoft<sup>&reg;</sup> Excel 或 Adobe<sup>&reg;</sup> Acrobat Reader 的情况下，通过 C# 将 CGM 文件导出为 TSV" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中轻松地将 CGM 文件转换为 TSV。首先，通过使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 CGM 导出到 XLSX。之后，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 电子表格编程 API，您可以将 XLSX 转换为 TSV。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 CGM 转换为 TSV" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开CGM文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将CGM转换为XLSX
3. 使用 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 类加载 XLSX 文档
4. 使用 [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 方法将文档保存为 TSV 格式，并将 `Tsv` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将受保护的 CGM 转换为 TSV" %}}
如果您的 CGM 文档受密码保护，则您无法在没有密码的情况下将其转换为 TSV。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，您可以初始化 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 类的新实例，并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 CGM 文件转换为带水印的 TSV" %}}
在将 CGM 文件转换为 TSV 时，您还可以在输出的 TSV 文件格式中添加水印。为了添加水印，您可以创建一个新的 Workbook 对象并打开转换后的 XLSX 文档，通过其索引选择 Worksheet，创建一个 Shape 并使用其 AddTextEffect 函数。之后，您可以将 XLSX 文档保存为带水印的 TSV。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 CGM 文件转换为 TSV：用例" %}}
将CGM文件格式转换为TSV格式是必要的，以充分释放您数据分析能力的潜力。

**用途：**

* **数据整合**：通过将CGM文件转换为TSV格式，实现与其他数据源和工具的无缝整合。
* **机器学习模型训练**：使用TSV格式数据训练机器学习模型，从而获得准确的预测和见解。
* **商业智能报告生成**：将CGM文件转换为TSV格式，创建交互式仪表盘、报表和可视化图表，以促进决策制定。
* **数据挖掘与分析**：利用TSV格式数据进行数据挖掘和分析任务，如识别模式、趋势和相关性。
* **云存储集成**：将CGM文件转换为TSV格式，便于上传到如AWS S3或Google Cloud Storage等云存储服务。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}