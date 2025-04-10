---
title: C# API 将 PS 导出到 DOTX
description: 在不使用 Microsoft Word 的情况下将 PS 转换为 DOTX
url_ignore: /zh/net/conversion/ps-to-dotx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: DOTX
otherformats: FLATOPC ODT PCL XAMLFLOW MHTML OTT MARKDOWN DOTX WORDML RTF DOTM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 PS 渲染到 DOTX" h2=".NET API 可在 Windows、macOS 和 Linux 上将 PS 导出为 DOTX，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 PS 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 DOTX。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 PS 转换为 DOTX" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开PS文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将PS转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为DOTX格式，并将Dotx设置为SaveFormat
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
在将 PS 转换为 DOTX 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 PS。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 PS 文件转换为 DOTX：用例" %}}
PS文件用于存储分层图形信息，非常适合创建包含多个元素的复杂文档。然而，在处理动态数据时，像Excel这样的电子表格成为数据可视化和分析的重要工具。

将PS文件转换为Excel格式是必要的，以充分发挥您的数据可视化和分析能力。这一转换使您能够：

**用途：**

* **数据分析**：将PS文件用于财务数据分析、跟踪市场趋势，并识别销售模式。
* **商业报告**：使用Excel进行业务表现可视化，创建报告，为利益相关者提供见解。
* **科学研究**：将PS文件用于模拟复杂系统、建模现实世界现象，以及分析实验数据。
* **营销活动**：使用Excel跟踪活动效果，优化策略，并衡量营销战术的有效性。
* **教育和培训**：将PS文件用于创建交互式演示、模拟以及教育用途的视觉辅助工具。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}