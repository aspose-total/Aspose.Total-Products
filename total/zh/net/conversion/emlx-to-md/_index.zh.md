---
title: 将 EMLX 导出为 MD 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMLX 转换为 MD
url_ignore: /zh/net/conversion/emlx-to-md/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: MD
otherformats: PDF OTT PCL JPEG RTF GIF DOC DOCX EMF EPUB TIFF DOTM TEXT DOT SVG ODT XPS PS WORDML DOTX PNG MD DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMLX 导出到 MD" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMLX 渲染为 MD，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMLX 到 MD 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMLX 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 MD。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMLX 转换为 MD" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMLX 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMLX 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 MD 格式，并将 Md 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMLX 文件" %}}
在将 EMLX 转换为 MD 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMLX 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 MD 文档编辑" %}}
在将文档从 EMLX 保存到 MD 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMLX 文件转换为 MD：用例" %}}
EMLX（电子邮件标记语言）文件用于存储带有格式信息的纯文本电子邮件，因此它们是创建基本电子邮件模板和组合的理想选择。然而，当处理结构化数据和可视化时，Markdown 文件变得至关重要，因为它们在数据呈现和分析中发挥着关键作用。

将 EMLX 文件转换为 Markdown 格式是必要的，以充分释放您数据可视化和分析能力的潜力。这种转换使您能够：

**用途：**

*   **项目文档**：将 EMLX 文件转换为易于阅读的项目文档，跟踪变更并与团队成员合作。
*   **会议笔记和纪要**：使用 Markdown 取会议笔记、记录会议纪要，并与出席者共享。
*   **个人日记**：将 EMLX 文件转换以维护个人日记或私人日记，记录思想、经历和反思。
*   **研究论文撰写**：使用 Markdown 创建并组织研究论文、文章和散文，以提高可读性并促进合作。
*   **知识库创建**：将 EMLX 文件转换以创建知识库，记录流程、程序和最佳实践，使其易于搜索和访问。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}