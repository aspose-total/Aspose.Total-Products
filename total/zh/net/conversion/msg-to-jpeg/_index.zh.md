---
title: 将 MSG 导出为 JPEG 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 MSG 转换为 JPEG
url_ignore: /zh/net/conversion/msg-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: DOT DOCX DOTX RTF TEXT GIF PCL SVG DOCM WORDML EPUB TIFF PNG ODT JPEG OTT XPS PDF FLATOPC DOC MD DOTM EMF PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MSG 导出到 JPEG" h2=".NET API 在 Windows、macOS 和 Linux 上将 MSG 渲染为 JPEG，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 MSG 到 JPEG 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 MSG 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 JPEG。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 MSG 转换为 JPEG" %}}
1. 使用 [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage) 类打开 MSG 文件
2. 使用 [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) 方法将 MSG 转换为 HTML
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

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 MSG 文件" %}}
在将 MSG 转换为 JPEG 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 MSG 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/msg) 的 [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 JPEG 文档编辑" %}}
在将文档从 MSG 保存到 JPEG 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MSG 文件转换为 JPEG：用例" %}}
MSG（消息）文件用于存储纯文本信息，是创建简单消息和通信的理想格式。然而，在处理图像和多媒体内容时，JPEG（联合摄影专家组）成为了必需的格式。

将MSG文件转换为JPEG格式是必要的，以充分发挥你的视觉内容分享与展示能力。此次转换使你能够：

**用途：**

*   **图片共享**：将MSG文件转换为JPEG，用于通过电子邮件或消息平台共享照片和图形。
*   **社交媒体发布**：使用JPEG格式在社交媒体平台上发布高质量图片，从而提升你的在线存在感。
*   **网站图形**：将MSG文件转换为创建视觉吸引人的网站图形，包括标志、图标和其他多媒体元素。
*   **图形设计项目**：使用JPEG存储和分享图形设计文件，如海报、传单和宣传册。
*   **数字故事讲述**：将MSG文件转换为创建交互式数字故事，包括动画和视频内容。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}