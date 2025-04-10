---
title: C# API 将 MD 导出到 DOTX
description: 在不使用 Microsoft Word 的情况下将 MD 转换为 DOTX
url_ignore: /zh/net/conversion/md-to-dotx/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOTX
otherformats: MHTML PS MARKDOWN DOTM DOT ODT DOTX RTF WORDML OTT FLATOPC XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MD 渲染到 DOTX" h2=".NET API 可在 Windows、macOS 和 Linux 上将 MD 导出为 DOTX，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 MD 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 DOTX。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 MD 转换为 DOTX" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开MD文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将MD转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为DOTX格式，并将Dotx设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 使用所有者密码解密 MD 文件" %}}
在将 MD 转换为 DOTX 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 MD。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 DOTX- 文件" %}}
为了保护您的 DOTX 不被编辑，并防止其他人编辑您文档中的敏感和机密信息，您还可以使用 API 设置文档的保护。您可以限制编辑文档的能力，只允许对其进行某些操作。这可以使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API 来完成。它使您能够控制使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数限制内容的方式。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MD 文件转换为 DOTX：用例" %}}
将 Markdown 文件（MD）转换为 DOTX（Microsoft Word XML）格式，有助于充分发挥您的文档出版和编辑功能。这种转换使您能够：

**用途：**

*   **技术写作与文档编写**：将 MD 文件转换为 DOTX 格式，创建易于阅读、可分享的文档，以满足技术受众，如用户手册、指南和产品文档。
*   **博客文章与文章**：使用 DOTX 格式来格式化博客文章和文章，使其具有专业布局、标题和格式，使其更具吸引力和可读性。
*   **演示与幻灯片展示**：将 MD 文件转换为 DOTX 格式，创建交互式幻灯片展示、演示和推销，适用于商务会议、产品发布会和营销活动。
*   **手册与指南**：使用 DOTX 格式来格式化技术手册和指南，使其具有清晰的说明、图表和插图，更易于理解和遵循。
*   **学术论文与期刊**：将 MD 文件转换为 DOTX 格式，创建格式规范的学术论文和期刊，以便在有声望的科学数据库中发表。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}