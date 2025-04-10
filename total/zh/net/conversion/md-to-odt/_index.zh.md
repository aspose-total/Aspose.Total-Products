---
title: C# API 将 MD 导出到 ODT
description: 在不使用 Microsoft Word 的情况下将 MD 转换为 ODT
url_ignore: /zh/net/conversion/md-to-odt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODT
otherformats: ODT PS XAMLFLOW DOTM MHTML DOT OTT DOTX WORDML MARKDOWN PCL RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MD 渲染到 ODT" h2=".NET API 可在 Windows、macOS 和 Linux 上将 MD 导出为 ODT，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 MD 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 ODT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 MD 转换为 ODT" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开MD文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将MD转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为ODT格式，并将Odt设置为SaveFormat
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
在将 MD 转换为 ODT 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 MD。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 ODT- 文件" %}}
为了保护您的 ODT 不被编辑，并防止其他人编辑您文档中的敏感和机密信息，您还可以使用 API 设置文档的保护。您可以限制编辑文档的能力，只允许对其进行某些操作。这可以使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API 来完成。它使您能够控制使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数限制内容的方式。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MD 文件转换为 ODT：用例" %}}
**文件格式转换：**

Markdown（MD）文件用于存储文本信息，适合用于创建文档、笔记和文章。然而，当处理结构化数据时，OpenDocument Text（ODT）格式成为必不可少的文档编辑和协作工具。

将 MD 文件转换为 ODT 格式是必要的，以充分发挥您文档编辑和协作功能的潜力。这项转换使您能够：

**用途：**

*   **文档和博客写作**：轻松创建结构化的文档、博客文章和文章。
*   **技术撰写**：使用 ODT 编辑并协作于技术文档，如用户手册、指南和说明材料。
*   **研究论文和学术写作**：将 MD 文件转换为格式化的研究论文、硕士论文和博士论文，利用高级功能。
*   **个人笔记和日记**：使用 ODT 组织个人笔记、日记条目和思考内容，以结构化和易读的格式呈现。
*   **内容管理系统（CMS）**：将 MD 文件转换为结构化内容，整合到 CMS 平台中，实现高效发布和管理。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}