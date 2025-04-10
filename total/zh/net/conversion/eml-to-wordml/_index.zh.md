---
title: 将 EML 导出为 WORDML 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EML 转换为 WORDML
url_ignore: /zh/net/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORDML
otherformats: FLATOPC ODT RTF DOT WORDML DOTX PCL TIFF XPS SVG JPEG MD DOCM OTT DOC DOTM PNG DOCX EPUB EMF TEXT PS PDF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EML 导出到 WORDML" h2=".NET API 在 Windows、macOS 和 Linux 上将 EML 渲染为 WORDML，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EML 到 WORDML 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EML 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 WORDML。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EML 转换为 WORDML" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EML 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 WORDML 格式，并将 Wordml 设置为 SaveFormat
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
在将 EML 转换为 WORDML 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EML 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/eml) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 WORDML 文档编辑" %}}
在将文档从 EML 保存到 WORDML 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.wordml", SaveFormat.Wordml);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EML 文件转换为 WORDML：用例" %}}
电子邮件文件（EML）用于存储纯文本消息，非常适合简单的电子邮件通信。但是，当处理基于文档的数据时，Word Markup Language（WordML）就变得至关重要了，因为它用于格式化和样式设置。

将 EML 文件转换为 WordML 格式，是为了解锁您在文件编辑和发布方面的全能功能。这种转换使您能够：

**用途：**

*   **文件编辑与出版**：将 EML 文件转换为 WordML 格式，以便进行文件编辑和出版，确保格式一致性和样式设置。
*   **电子邮件模板与简历**：使用 WordML 创建专业看起来的电子邮件模板和简历，以展示您的技能和经验。
*   **报告生成与发布**：将 EML 文件转换为 WordML 格式，用于生成报告和出版物，如文章、白皮书等。
*   **营销活动材料**：使用 WordML 创建营销活动的宣传资料，如手册、传单和社交媒体内容。
*   **学术与研究写作**：将 EML 文件转换为格式化的学术和研究论文、硕士论文和博士论文，确保正确引用和参考。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}