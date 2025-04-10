---
title: 通过 C# API 将 EPUB 导出到 ODP
description: .NET API 在不使用 Microsoft Word 的情况下将 EPUB 转换为 ODP
url_ignore: /zh/net/conversion/epub-to-odp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODP
otherformats: POTM OTP POWERPOINT POTX POT PPS XAML PPSX PPTM PPT PPSM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EPUB 渲染到 ODP" h2=".NET API 可在 Windows、macOS 和 Linux 上将 EPUB 导出为 ODP，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用功能强大的文件格式自动化 API 包 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 EPUB 渲染为 ODP。通过使用 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 EPUB 文件格式转换为 PPTX。之后，通过使用 Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPTX 转换为 ODP。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API 将 EPUB 转换为 ODP" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开EPUB文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将EPUB转换为PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载 PPTX 文件
4. 使用 [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) 方法将文档保存为 ODP 格式，并将 `Odp` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 从 EPUB 文件中获取 XMP 元数据" %}}
在将 EPUB 转换为 ODP 时，您可能需要额外的 XMP 元数据信息来确定批量转换过程的优先级。例如，您可以根据创建日期获取转换文档并对其进行排序，并相应地处理文档。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) 允许您访问 EPUB 文件的 XMP 元数据。要获取 EPUB 文件的元数据，您可以创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并打开输入的 EPUB 文件。之后，您可以使用 [元数据](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) 属性获取文件的元数据。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(
{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 ODP 文件" %}}
通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API，您可以进一步增强转换应用程序的功能。其中一项功能可以是创建只读输出文件以提高安全性。 API 允许您将 ODP 文件设置为只读，这意味着用户(在打开演示文稿后)会看到只读建议。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EPUB 文件转换为 ODP：用例" %}}
EPUB（电子出版）文件用于存储内容，是制作数字出版物和电子书的理想格式。然而，在使用 LibreOffice 等演示文稿软件时，它们变得至关重要，用于演示文稿的创建和设计。

将 EPUB 文件转换为 ODP（开放文档演示文稿）格式是必要的，以充分发挥您在制作演示文稿方面的能力。这种转换使您能够：

**用途：**

* **企业演示文稿**：将 EPUB 文件用于创建吸引人的企业演示文稿，包括幻灯片展示、信息图表和多媒体内容。
* **教育资源**：使用 ODP 格式开发交互式教育资源，如教程、讲座和学生材料。
* **营销材料**：将 EPUB 文件转换为视觉吸引人的营销材料，如销售手册、产品演示和客户演示文稿。
* **培训内容**：使用 ODP 格式设计交互式培训内容，包括研讨会、网络研讨会和在线课程。
* **商业提案和推广牌**：将 EPUB 文件用于创建专业的商业提案、推广牌和执行总结。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}