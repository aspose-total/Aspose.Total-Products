---
title: 将 MSG 导出为 DOT 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 MSG 转换为 DOT
url_ignore: /zh/net/conversion/msg-to-dot/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOT
otherformats: TEXT FLATOPC XPS DOCM DOTM RTF OTT EMF PCL ODT GIF JPEG PDF PS WORDML DOCX DOC MD SVG TIFF PNG DOTX DOT EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MSG 导出到 DOT" h2=".NET API 在 Windows、macOS 和 Linux 上将 MSG 渲染为 DOT，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 MSG 到 DOT 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 MSG 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 DOT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 MSG 转换为 DOT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage) 类打开 MSG 文件
2. 使用 [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) 方法将 MSG 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 DOT 格式，并将 Dot 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 MSG 文件" %}}
在将 MSG 转换为 DOT 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 MSG 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/msg) 的 [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 DOT 文档编辑" %}}
在将文档从 MSG 保存到 DOT 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MSG 文件转换为 DOT：用例" %}}
MSG（消息文件）文件用于存储基于文本的信息，非常适合在网络中发送和接收信息。然而，当处理视觉数据时，像PNG这样的图像格式就变得至关重要了，因为它们适合分享静态图片和插图。

将MSG文件转换为PNG格式是必要的，以充分发挥您在图形内容共享方面的潜力。这使得您能够：

**用途：**

*   **社交媒体分享**：将MSG文件转换为PNG格式，以便在社交媒体平台上分享消息，实现与朋友和粉丝的即时通信。
*   **邮件附件优化**：使用PNG格式来优化电子邮件附件，确保文本清晰显示，并减小文件大小以提高传输效率。
*   **文字转语音集成**：将MSG文件转换为文本内容，例如有声书或播客，以提高可访问性和参与度。
*   **基于图像的故事讲述**：使用PNG格式来可视化复杂数据，如信息图表，并通过吸引人的图形分享故事。
*   **屏幕捕获和录制**：将MSG文件转换为PNG格式，以捕获并记录屏幕活动，创建教程、演示或直播内容。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}