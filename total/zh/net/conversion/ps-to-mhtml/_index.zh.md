---
title: C# API 将 PS 导出到 MHTML
description: 在不使用 Microsoft Word 的情况下将 PS 转换为 MHTML
url_ignore: /zh/net/conversion/ps-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MHTML
otherformats: DOTM OTT RTF DOTX FLATOPC DOT WORDML ODT MARKDOWN PCL MHTML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 PS 渲染到 MHTML" h2=".NET API 可在 Windows、macOS 和 Linux 上将 PS 导出为 MHTML，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 PS 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 MHTML。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 PS 转换为 MHTML" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开PS文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将PS转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为MHTML格式，并将Mhtml设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 使用所有者密码解密 PS 文件" %}}
在将 PS 转换为 MHTML 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 PS。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 MHTML- 文件" %}}
为了保护您的 MHTML 不被编辑，并防止其他人编辑您文档中的敏感和机密信息，您还可以使用 API 设置文档的保护。您可以限制编辑文档的能力，只允许对其进行某些操作。这可以使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API 来完成。它使您能够控制使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数限制内容的方式。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 PS 文件转换为 MHTML：用例" %}}
PDF（便携式文档格式）文件用于存储静态图形信息，因此在创建出版物和文档时非常理想。然而，当处理动态数据时，基于网络的应用程序，如Internet Explorer，成为数据可视化和分析的必要工具。

将 PDF 文件转换为 MHTML 格式是必要的，以解锁您数据可视化和分析潜力的全部可能性。这项转换使您能够：

**用途：**

*   **电子商务网站分析**：将 PDF 文件转换以分析电子商务网站数据，跟踪销售趋势，并识别客户行为模式。
*   **文档审查与比较**：使用 MHTML 审核和比较文档，跟踪变更并衡量文档准确性。
*   **技术支持知识库**：将 PDF 文件转换以创建交互式技术支持知识库，模拟用户体验，并验证文档概念。
*   **研究论文发表**：使用 MHTML 可视化复杂的研究数据，如 3D 模型、仿真结果和实验数据，以一种可以发表的格式进行可视化。
*   **合规报告与仪表盘**：将 PDF 文件转换以创建交互式仪表盘、报告和可视化工具，以满足法规合规要求，从而提高决策质量。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}