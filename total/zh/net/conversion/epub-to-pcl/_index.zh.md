---
title: C# API 将 EPUB 导出到 PCL
description: 在不使用 Microsoft Word 的情况下将 EPUB 转换为 PCL
url_ignore: /zh/net/conversion/epub-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PCL
otherformats: DOTX ODT PS DOT RTF MHTML PCL OTT FLATOPC DOTM WORDML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EPUB 渲染到 PCL" h2=".NET API 可在 Windows、macOS 和 Linux 上将 EPUB 导出为 PCL，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 EPUB 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 PCL。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EPUB 转换为 PCL" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开EPUB文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将EPUB转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为PCL格式，并将Pcl设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 使用所有者密码解密 EPUB 文件" %}}
在将 EPUB 转换为 PCL 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 EPUB。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 PCL- 文件" %}}
为了保护您的 PCL 不被编辑，并防止其他人编辑您文档中的敏感和机密信息，您还可以使用 API 设置文档的保护。您可以限制编辑文档的能力，只允许对其进行某些操作。这可以使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API 来完成。它使您能够控制使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数限制内容的方式。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EPUB 文件转换为 PCL：用例" %}}
电子书文件（Electronic Publication Format，Epub）用于存储数字内容，是创建交互式多媒体文档的理想格式。然而，在处理印刷定制需求时，可打印内容文件（Printable Content File，PCF）变得至关重要，以实现对布局和格式的精确控制。

将电子书文件转换为PCF格式是必要的，以充分发挥您的印刷定制能力。这一转换使您能够：

**应用场景：**

*   **高质量打印**：将电子书文件转换以创建专业级的印刷材料，包括宣传手册、传单和其他营销资料。
*   **定制布局**：使用PCF设计定制的印刷材料布局，确保精准对齐和格式设置。
*   **精确页面布局**：将电子书文件转换以创建具有精确控制页脚、边框等元素的页面布局，减少错误并提高效率。
*   **物料优化**：使用PCF优化适用于特定行业或应用的打印材料，如房地产、金融或医疗领域。
*   **快速回转时间**：将电子书文件转换为PCF文件以实现快速印刷定制生产，允许快速回转时间并高效管理供应链。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}