---
title: 将 MSG 导出为 OTT 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 MSG 转换为 OTT
url_ignore: /zh/net/conversion/msg-to-ott/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: OTT
otherformats: FLATOPC DOTX PNG RTF EPUB GIF MD WORDML ODT PS EMF PDF JPEG DOCM DOT DOCX SVG DOC PCL OTT DOTM TEXT XPS TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MSG 导出到 OTT" h2=".NET API 在 Windows、macOS 和 Linux 上将 MSG 渲染为 OTT，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 MSG 到 OTT 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 MSG 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 OTT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 MSG 转换为 OTT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage) 类打开 MSG 文件
2. 使用 [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) 方法将 MSG 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 OTT 格式，并将 Ott 设置为 SaveFormat
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
在将 MSG 转换为 OTT 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 MSG 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/msg) 的 [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 OTT 文档编辑" %}}
在将文档从 MSG 保存到 OTT 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MSG 文件转换为 OTT：用例" %}}
MSG (消息文件)用于存储基于文本的信息，是在网络上发送消息的理想选择。然而，当处理多媒体数据时，超级应用(Over-the-top, OTT)服务就变得至关重要，因为它们用于视频流播放和内容分发。

将MSG文件转换为OTT格式是必要的，以充分发挥您的视频流播放和内容分发能力。这一转换使您能够实现以下用途：

**用途：**

*   **视频流优化**：将MSG文件转换为分析视频流数据、追踪观众互动并优化播放质量。
*   **内容推荐引擎**：利用OTT格式创建个性化内容推荐，改善用户体验并增加观看量。
*   **社交媒体集成**：将MSG文件转换为在OTT服务中集成社交媒体平台，从而增强用户参与和互动。
*   **直播事件传播**：使用OTT格式来播放直播事件，实现实时互动并提供沉浸式观看体验。
*   **数据分析与洞察**：将MSG文件转换为分析OTT服务数据、追踪用户行为并获取有价值的业务增长见解。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}