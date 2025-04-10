---
title: 通过 C# API 将 PS 导出到 POTM
description: .NET API 在不使用 Microsoft Word 的情况下将 PS 转换为 POTM
url_ignore: /zh/net/conversion/ps-to-potm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTM
otherformats: POT POTX XAML PPSM OTP POWERPOINT PPSX PPTM PPT SWF PPS POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 PS 渲染到 POTM" h2=".NET API 可在 Windows、macOS 和 Linux 上将 PS 导出为 POTM，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用功能强大的文件格式自动化 API 包 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 PS 渲染为 POTM。通过使用 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 PS 文件格式转换为 PPTX。之后，通过使用 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPTX 转换为 POTM。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 PS 转换为 POTM" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开PS文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将PS转换为PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PPTX 文件
4. 使用 [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 方法将文档保存为 POTM 格式，并将 `Potm` 设置为 SaveFormat
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
在将 PS 转换为 POTM 时，您可能需要额外的 XMP 元数据信息来确定批量转换过程的优先级。例如，您可以根据创建日期获取转换文档并对其进行排序，并相应地处理文档。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) 允许您访问 PS 文件的 XMP 元数据。要获取 PS 文件的元数据，您可以创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并打开输入的 PS 文件。之后，您可以使用 [元数据](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 属性获取文件的元数据。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(
{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 POTM 文件" %}}
通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API，您可以进一步增强转换应用程序的功能。其中一项功能可以是创建只读输出文件以提高安全性。 API 允许您将 POTM 文件设置为只读，这意味着用户(在打开演示文稿后)会看到只读建议。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 PS 文件转换为 POTM：用例" %}}
PDF（便携式文档格式）文件用于存储文档信息，适合制作静态文档和出版物。但当处理动态数据时，演示软件如PowerPoint成为创建演示和可视化的必要工具。

将PDF文件转换为PowerPoint格式是必要的，以解锁您呈现和可视化能力的最大潜力。这种转换使您能够：

**用途：**

*   **企业演示设计**：将PDF文件用于制作吸引人的企业演示、幻灯片展示和叙事。
*   **营销活动演示**：使用PowerPoint可视化营销活动数据，优化策略并以交互方式测量ROI。
*   **教育内容创建**：将PDF文件转换为交互式教育内容，如测试、游戏和模拟。
*   **研究出版准备**：使用PowerPoint格式研究论文、报告等文档以备发表。
*   **演示和提案**：将PDF文件用于制作动态演示和提案，以吸引观众并清晰地传达复杂信息。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}