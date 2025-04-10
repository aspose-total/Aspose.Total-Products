---
title: 通过 C# API 将 PS 导出到 POT
description: .NET API 在不使用 Microsoft Word 的情况下将 PS 转换为 POT
url_ignore: /zh/net/conversion/ps-to-pot/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POT
otherformats: POT PPSM PPS SWF XAML POWERPOINT POTX POTM PPSX PPTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 PS 渲染到 POT" h2=".NET API 可在 Windows、macOS 和 Linux 上将 PS 导出为 POT，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用功能强大的文件格式自动化 API 包 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 PS 渲染为 POT。通过使用 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 PS 文件格式转换为 PPTX。之后，通过使用 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPTX 转换为 POT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 PS 转换为 POT" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开PS文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将PS转换为PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PPTX 文件
4. 使用 [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 方法将文档保存为 POT 格式，并将 `Pot` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 从 PS 文件中获取 XMP 元数据" %}}
在将 PS 转换为 POT 时，您可能需要额外的 XMP 元数据信息来确定批量转换过程的优先级。例如，您可以根据创建日期获取转换文档并对其进行排序，并相应地处理文档。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) 允许您访问 PS 文件的 XMP 元数据。要获取 PS 文件的元数据，您可以创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并打开输入的 PS 文件。之后，您可以使用 [元数据](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 属性获取文件的元数据。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(
{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 POT 文件" %}}
通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API，您可以进一步增强转换应用程序的功能。其中一项功能可以是创建只读输出文件以提高安全性。 API 允许您将 POT 文件设置为只读，这意味着用户(在打开演示文稿后)会看到只读建议。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 PS 文件转换为 POT：用例" %}}
PDF（便携式文档格式）文件用于存储位图图像信息，因此在创建出版物、文档和演示文稿方面非常理想。然而，当处理动态数据时，电子表格软件如Excel在数据分析和可视化方面变得至关重要。

将PDF文件转换为Excel格式是必要的，以解锁您数据分析和可视化潜力的全部可能性。这一转换使您能够：

**用途：**

*   **商业智能分析**：将PDF文件用于分析销售趋势、跟踪客户行为并识别数据模式。
*   **市场研究与竞争对手分析**：使用Excel可视化市场份额数据，分析竞争对手策略，并衡量品牌表现。
*   **财务报告与预算**：将PDF文件转换为交互式财务报告，跟踪费用并预测收入增长。
*   **营销自动化与潜在客户追踪**：使用Excel分析营销活动结果，跟踪潜在客户生成并优化销售渠道。
*   **数据科学与机器学习**：将PDF文件用于从文本数据中提取见解，进行情感分析，并构建预测模型。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}