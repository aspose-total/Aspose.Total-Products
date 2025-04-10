---
title: 将 EML 导出为 TEXT 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EML 转换为 TEXT
url_ignore: /zh/net/conversion/eml-to-text/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TEXT
otherformats: PNG DOT DOTM JPEG ODT MD XPS PS WORDML DOCX FLATOPC EPUB SVG TIFF DOTX RTF OTT DOCM DOC PDF PCL GIF TEXT EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EML 导出到 TEXT" h2=".NET API 在 Windows、macOS 和 Linux 上将 EML 渲染为 TEXT，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EML 到 TEXT 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EML 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 TEXT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EML 转换为 TEXT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EML 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 TEXT 格式，并将 Text 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EML 文件" %}}
在将 EML 转换为 TEXT 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EML 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/eml) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 TEXT 文档编辑" %}}
在将文档从 EML 保存到 TEXT 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EML 文件转换为 TEXT：用例" %}}
电子邮件文件（EML）用于存储基于文本的通信信息，使其成为可读邮件和电子邮件的理想格式。然而，当处理多媒体内容时，像PDF这样的文件成为了分享和查看的必要工具。

将EML文件转换为文本格式是必要的，以解锁您消息内容和分析能力的完全潜力。这项转换使您能够：

**用途：**

*   **信息分析**：将EML文件转换以分析电子邮件内容，跟踪发信人的行为，并识别通信模式。
*   **电子邮件营销自动化**：使用文本格式可视化电子邮件营销数据，自动触发营销活动，并衡量开封率。
*   **客户支持文档**：将EML文件转换以创建易于阅读的文档、FAQ和知识库，以便为客户提供更好的技术支持服务。
*   **历史记录保存**：使用文本格式存储并检索历史电子邮件记录，确保符合法规和记录保存要求。
*   **内容再利用**：将EML文件转换以创建可分享的内容，如博客文章、社交媒体更新和新闻稿，以提高参与度和覆盖范围。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}