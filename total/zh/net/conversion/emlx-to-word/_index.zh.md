---
title: 将 EMLX 导出为 WORD 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMLX 转换为 WORD
url_ignore: /zh/net/conversion/emlx-to-word/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: PS SVG FLATOPC EMF OTT JPEG PCL WORD PDF TEXT XPS GIF ODT PNG RTF DOTX DOC MD EPUB WORDML DOCM TIFF DOT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMLX 导出到 WORD" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMLX 渲染为 WORD，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMLX 到 WORD 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMLX 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 WORD。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMLX 转换为 WORD" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMLX 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMLX 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 WORD 格式，并将 Word 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMLX 文件" %}}
在将 EMLX 转换为 WORD 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMLX 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 WORD 文档编辑" %}}
在将文档从 EMLX 保存到 WORD 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.word", SaveFormat.Word);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMLX 文件转换为 WORD：用例" %}}
EMLX (电子邮件附加文件)文件用于存储基于文本的信息，使其成为创建电子邮件消息和文档的理想工具。然而，当处理富媒体内容时，微软 Word 成为格式化文档和演示的必要工具。

将 EMLX 文件转换为微软 Word 格式是解锁您文档格式化和演示潜力必需的步骤。这一转换使您能够：

**用途：**

*   **商务对话优化**：将 EMLX 文件转换为专业商务文件，优化格式，并提高可读性。
*   **技术写作与文档编写**：使用微软 Word 格式化技术写作，创建用户手册，并开发指南内容。
*   **学术研究与论文**：将 EMLX 文件转换为格式化的学术论文，优化引用，提高参考文献。
*   **个人对话管理**：使用微软 Word 管理个人对话，优化电子邮件模板，并简化通信。
*   **文档协作与审阅**：将 EMLX 文件转换为协作文档，跟踪变更，确保无缝文档审阅。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}