---
title: 将 EMLX 导出为 OTT 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMLX 转换为 OTT
url_ignore: /zh/net/conversion/emlx-to-ott/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: OTT
otherformats: RTF OTT ODT DOT TEXT TIFF WORDML PS SVG PNG MD EMF EPUB FLATOPC DOTX DOCX GIF PDF DOCM JPEG XPS DOC DOTM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMLX 导出到 OTT" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMLX 渲染为 OTT，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMLX 到 OTT 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMLX 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 OTT。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMLX 转换为 OTT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMLX 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMLX 转换为 HTML
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

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMLX 文件" %}}
在将 EMLX 转换为 OTT 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMLX 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 OTT 文档编辑" %}}
在将文档从 EMLX 保存到 OTT 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMLX 文件转换为 OTT：用例" %}}
EMLX (电子邮件标记语言)文件用于存储基于文本的电子邮件内容，是创建无格式化的纯文本电子邮件的理想选择。然而，当处理富媒体数据时，像OTT这样的Office文档就变得至关重要了，以便进行内容创作和分析。

将EMLX文件转换为OTT格式是必要的，以充分发挥您在内容创作和分析方面的能力。这项转换使您能够：

**用途：**

*   **电子邮件模板定制**：将EMLX文件转换为创建可自定义电子邮件模板、个性化发送信息以及增强品牌一致性的工具。
*   **数字资产管理**：利用OTT来管理和视觉化数字资产，如图片、视频和文档，以便跨多个电子邮件活动使用。
*   **垃圾邮件过滤训练数据**：将EMLX文件转换为训练高级垃圾邮件过滤器的数据，从而提高电子邮件投递率并减少钓鱼攻击尝试。
*   **客户沟通分析**：分析OTT文件以获取关于客户行为、偏好和反馈的见解，以指导未来营销策略。
*   **电子邮件安全与合规性**：利用OTT识别并修复安全威胁，确保符合监管要求和行业标准。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}