---
title: C# API 将 CGM 导出到 XAMLFLOW
description: 在不使用 Microsoft Word 的情况下将 CGM 转换为 XAMLFLOW
url_ignore: /zh/net/conversion/cgm-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XAMLFLOW
otherformats: MARKDOWN DOTX XAMLFLOW OTT ODT DOTM DOT WORDML PCL MHTML FLATOPC RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 CGM 渲染到 XAMLFLOW" h2=".NET API 可在 Windows、macOS 和 Linux 上将 CGM 导出为 XAMLFLOW，而无需使用 Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) 是一个强大的 API，用于在您的 .NET 应用程序中添加文档操作和转换功能。通过使用高级 PDF 处理 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 CGM 文件格式转换为 DOC。之后，通过使用强大的文档处理 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 DOC 渲染为 XAMLFLOW。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 CGM 转换为 XAMLFLOW" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开CGM文件
2. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将CGM转换为Doc
3. 用Aspose.Words的[Document](https://reference.aspose.com/words/net/aspose.words/document)类加载Doc文件
4. 使用[Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)方法将文档保存为XAMLFLOW格式，并将Xamlflow设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.xamlflow", SaveFormat.Xamlflow);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 使用所有者密码解密 CGM 文件" %}}
在将 CGM 转换为 XAMLFLOW 之前，如果您想解密您的文档，您可以使用 API 来完成。为了解密 PDF 文件，您首先需要创建一个 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 对象并使用所有者的密码打开 CGM。之后，您需要调用 Document 对象的 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 方法。最后，使用 Document 对象的 Save 方法保存更新的文件。  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 创建只读 XAMLFLOW- 文件" %}}
为了保护您的 XAMLFLOW 不被编辑，并防止其他人编辑您文档中的敏感和机密信息，您还可以使用 API 设置文档的保护。您可以限制编辑文档的能力，只允许对其进行某些操作。这可以使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API 来完成。它使您能够控制使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数限制内容的方式。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xamlflow", SaveFormat.Xamlflow);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 CSV 文件转换为 ODT：用例" %}}
逗号分隔值文件（CSV）用于存储表格数据，是制作和编辑电子表格的理想选择。然而，在处理文档格式时，开放文档文本文件（ODT）成为协作写作和出版的重要文件。

将 CSV 文件转换为 ODT 格式是实现您协作写作和出版能力的关键。这一转换使您能够：

**用途：**

*   **协作文档编辑**：将 CSV 文件转换为可编辑的文档，协作与团队成员合作，并分享修订版本。
*   **数据驱动报告**：使用 ODT 查看数据见解、生成报告并创建演示文稿，以便向利益相关者做出更好的决策。
*   **内容管理**：将 CSV 文件转换为管理内容库，自动化工作流程，并在集中平台上跟踪变更。
*   **发布与分享**：使用 ODT 创建可分享的文档，与作者协作并高效分发出版物。
*   **智能格式化**：将 CSV 文件转换为自动格式化文字、图像和布局，以确保一致性和专业性。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}