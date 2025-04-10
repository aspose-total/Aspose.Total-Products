---
title: C# API 将 PS 导出到 ODT
description: 在不使用 Microsoft Word 的情况下将 PS 转换为 ODT
url_ignore: /zh/net/conversion/ps-to-odt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODT
otherformats: RTF WORDML DOTM ODT OTT DOTX XAMLFLOW FLATOPC DOT MHTML PCL MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 PS 渲染到 ODT" h2=".NET API 可在 Windows、macOS 和 Linux 上将 PS 导出为 ODT，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 PS 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 ODT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 PS 转换为 ODT" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开PS文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将PS转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为ODT格式，并将Odt设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 使用所有者密码解密 PS 文件" %}}
在将 PS 转换为 ODT 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 PS。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 PS 文件转换为 ODT：用例" %}}
PS（Portable Document Format，简称PDF）文件用于存储文档，是制作静态文档和出版物的理想选择。然而，在处理动态数据时，像OpenDocument Text（ODT）这样的电子表格文件就变得至关重要，以支持文档编辑和协作。

将PS文件转换为ODT格式是必要的，以解锁您在文档编辑和协作方面的全部潜力。这项转换使您能够：

**用途：**

* **学术研究**：将PS文件转换为ODT格式以编辑学术文章、论文和毕业论文，与同事协作并分享研究成果。
* **技术写作**：使用ODT创建和编辑技术文档，如软件应用程序的用户手册、设备指南和操作说明，以描述硬件设备和工程过程。
* **商业演示**：将PS文件转换为ODT格式以制作吸引人的演示文稿、报告和提案，适用于企业通信、商务会议和行业活动。
* **出版与媒体**：使用ODT编辑发表在出版物、网站或在线媒体平台上的文章、故事等内容。
* **个人项目**：将PS文件转换为ODT格式以创建定制化文档，如简历、证书和信件，满足个人的需求。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}