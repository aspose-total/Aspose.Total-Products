---
title: 将 EML 导出为 JPEG 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EML 转换为 JPEG
url_ignore: /zh/net/conversion/eml-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: JPEG
otherformats: FLATOPC DOTX DOC PDF EPUB DOCM DOTM JPEG TEXT PCL PS OTT DOCX GIF MD XPS RTF SVG PNG WORDML DOT EMF TIFF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EML 导出到 JPEG" h2=".NET API 在 Windows、macOS 和 Linux 上将 EML 渲染为 JPEG，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EML 到 JPEG 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EML 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 JPEG。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EML 转换为 JPEG" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EML 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 JPEG 格式，并将 Jpeg 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EML 文件" %}}
在将 EML 转换为 JPEG 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EML 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/eml) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 JPEG 文档编辑" %}}
在将文档从 EML 保存到 JPEG 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EML 文件转换为 JPEG：用例" %}}
电子邮件（EML）文件用于存储基于文本的消息，因此它们是创建简单视觉化的邮件内容预览或摘录的理想选择。然而，当需要处理具有吸引眼球的图形和多媒体元素的内容时，JPEG（联合摄影专家组）图片格式就变得至关重要了，以便于分享和展示数据。

将电子邮件文件（EML）转换为JPEG格式是必要的，以充分发挥您在数据呈现和共享方面的能力。这种转换使您能够：

**用途：**

* **电子邮件营销活动**：将EML文件转换为视觉吸引力强的电子邮件营销活动，包括图片预览、社交媒体帖子和内容摘录。
* **新闻简报和博客**：使用JPEG格式展示电子邮件新闻简报和博客文章，使其对读者更具吸引力。
* **社交媒体分享**：将EML文件转换为在Twitter、Facebook或LinkedIn等社交平台上分享邮件内容的视觉化图片。
* **电子邮件客户端集成**：将EML文件转换为具有吸引人界面的定制电子邮件客户端和用户体验。
* **数据呈现和报告**：使用JPEG格式以更吸引人的方式展示数据，使利益相关者更容易理解复杂信息。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}