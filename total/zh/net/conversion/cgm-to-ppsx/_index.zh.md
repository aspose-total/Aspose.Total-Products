---
title: 通过 C# API 将 CGM 导出到 PPSX
description: .NET API 在不使用 Microsoft Word 的情况下将 CGM 转换为 PPSX
url_ignore: /zh/net/conversion/cgm-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPSX
otherformats: PPT POWERPOINT POTX POTM PPS SWF PPSM PPTM XAML OTP POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 CGM 渲染到 PPSX" h2=".NET API 可在 Windows、macOS 和 Linux 上将 CGM 导出为 PPSX，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用功能强大的文件格式自动化 API 包 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 CGM 渲染为 PPSX。通过使用 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 CGM 文件格式转换为 PPTX。之后，通过使用 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPTX 转换为 PPSX。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 CGM 转换为 PPSX" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开CGM文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将CGM转换为PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PPTX 文件
4. 使用 [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 方法将文档保存为 PPSX 格式，并将 `Ppsx` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 从 CGM 文件中获取 XMP 元数据" %}}
在将 CGM 转换为 PPSX 时，您可能需要额外的 XMP 元数据信息来确定批量转换过程的优先级。例如，您可以根据创建日期获取转换文档并对其进行排序，并相应地处理文档。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) 允许您访问 CGM 文件的 XMP 元数据。要获取 CGM 文件的元数据，您可以创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并打开输入的 CGM 文件。之后，您可以使用 [元数据](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 属性获取文件的元数据。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(
{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 PPSX 文件" %}}
通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API，您可以进一步增强转换应用程序的功能。其中一项功能可以是创建只读输出文件以提高安全性。 API 允许您将 PPSX 文件设置为只读，这意味着用户(在打开演示文稿后)会看到只读建议。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 CGM 文件转换为 PPSX：用例" %}}
将CGM（计算机图形元文件）文件转换为PPSX（微软PowerPoint XML演示文件）能够解锁您的数据可视化和分析潜力。这一转换是为了充分利用PowerPoint的交互功能，如动画、过渡和多媒体内容。

将CGM文件转换为PPSX格式具有以下用途：

**应用场景：**

*   **演示设计与开发**：将CGM文件转换为PPSX以创建吸引观众的演示、模拟以及交互式可视化，抓住听众注意力。
*   **数据驱动的故事讲述**：使用PPSX整合复杂的数据见解到演示中，以通过故事和可视化有效传达您的信息。
*   **企业沟通与报告**：将CGM文件转换为PPSX以创建专业报告、仪表盘和可视化，向利益相关者提供决策支持。
*   **营销及广告活动**：利用PPSX的多媒体功能，将动态内容、动画和视频整合到演示中，以增强营销信息和广告效果。
*   **学术与研究演示**：使用PPSX创建包含复杂数据可视化、模拟和多媒体元素的专业级研究演示。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}