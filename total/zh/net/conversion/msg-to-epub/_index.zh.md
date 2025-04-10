---
title: 将 MSG 导出为 EPUB 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 MSG 转换为 EPUB
url_ignore: /zh/net/conversion/msg-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: PDF DOT DOTM DOCM GIF SVG OTT XPS PS TEXT RTF PCL ODT EPUB DOC TIFF FLATOPC WORDML PNG EMF MD JPEG DOTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 MSG 导出到 EPUB" h2=".NET API 在 Windows、macOS 和 Linux 上将 MSG 渲染为 EPUB，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 MSG 到 EPUB 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 MSG 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 EPUB。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 MSG 转换为 EPUB" %}}
1. 使用 [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage) 类打开 MSG 文件
2. 使用 [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) 方法将 MSG 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 EPUB 格式，并将 Epub 设置为 SaveFormat
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

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 MSG 文件" %}}
在将 MSG 转换为 EPUB 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 MSG 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/msg) 的 [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 EPUB 文档编辑" %}}
在将文档从 MSG 保存到 EPUB 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 MSG 文件转换为 EPUB：用例" %}}
MSG（消息文件）文件用于存储纯文本数据，是应用程序之间交换信息的理想选择。然而，在使用数字出版工具如EPUB（电子出版物）时，MSG文件变得至关重要，因为它们在转换和分发过程中起着关键作用。

将MSG文件转换为EPUB格式是实现您的数字内容最大潜力的必要步骤。这一转换使您能够：

**用途：**

*   **电子书出版**: 将MSG文件转换为创建交互式电子书、文章和博客帖子，方便在线分享。
*   **数字杂志**: 使用EPUB格式来视觉化杂志内容，包括文章、图片和视频，并支持在线订阅管理。
*   **新闻简报和新闻稿**: 将MSG文件转换为发送定向新闻简报和新闻稿给订阅者和利益相关者。
*   **学术和研究出版物**: 使用EPUB格式发布研究论文、硕士论文和博士论文，作为数字化格式发布。
*   **数字资产管理**: 将MSG文件转换以创建一个集中仓库来存储图片、视频和音频文件。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}