---
title: 通过 C# API 将 MD 导出到 PPT
description: .NET API 在不使用 Microsoft Word 的情况下将 MD 转换为 PPT
url_ignore: /zh/net/conversion/md-to-ppt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PPT
otherformats: OTP PPT PPSX PPSM SWF POTM PPTM POWERPOINT PPS XAML POTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MD 渲染到 PPT" h2=".NET API 可在 Windows、macOS 和 Linux 上将 MD 导出为 PPT，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用功能强大的文件格式自动化 API 包 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 MD 渲染为 PPT。通过使用 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 MD 文件格式转换为 PPTX。之后，通过使用 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPTX 转换为 PPT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 MD 转换为 PPT" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开MD文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将MD转换为PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PPTX 文件
4. 使用 [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 方法将文档保存为 PPT 格式，并将 `Ppt` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 从 MD 文件中获取 XMP 元数据" %}}
在将 MD 转换为 PPT 时，您可能需要额外的 XMP 元数据信息来确定批量转换过程的优先级。例如，您可以根据创建日期获取转换文档并对其进行排序，并相应地处理文档。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) 允许您访问 MD 文件的 XMP 元数据。要获取 MD 文件的元数据，您可以创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并打开输入的 MD 文件。之后，您可以使用 [元数据](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 属性获取文件的元数据。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(
{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 PPT 文件" %}}
通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API，您可以进一步增强转换应用程序的功能。其中一项功能可以是创建只读输出文件以提高安全性。 API 允许您将 PPT 文件设置为只读，这意味着用户(在打开演示文稿后)会看到只读建议。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MD 文件转换为 PPT：用例" %}}
**Markdown (MD) 文件**是创建静态文档（如文档、笔记和报告）的理想格式。然而，在处理动态演示时，**PowerPoint (PPT)** 格式变得至关重要，因为它们有助于可视化和提高参与度。

将 **MD 文件** 转换为 **PPT 格式** 是必要的，以充分发挥你的演示潜力。这项转换使你能够：

**用途：**

*   **企业展示**：将 MD 文件转换为创建吸引人的企业展示，直观呈现关键信息，并展示公司成就。
*   **技术文档**：使用 PPT 以交互式格式呈现技术文档，使读者更容易理解复杂信息。
*   **学术研究演示**：将 MD 文件转换为专业的研究演示，轻松分享发现并直观展示方法论。
*   **营销材料**：利用 PPT 设计吸引眼球的营销材料，包括销售单页、宣传册和产品指南。
*   **培训与教学内容**：将 MD 文件转换为交互式培训内容，使用动画、过渡效果和多媒体元素以增强学习体验。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}