---
title: 将 EML 导出为 PS 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EML 转换为 PS
url_ignore: /zh/net/conversion/eml-to-ps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PS
otherformats: FLATOPC DOCM DOCX PNG XPS ODT DOC DOT SVG PCL PDF DOTM EPUB RTF GIF EMF WORDML JPEG MD PS DOTX TEXT OTT TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EML 导出到 PS" h2=".NET API 在 Windows、macOS 和 Linux 上将 EML 渲染为 PS，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EML 到 PS 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EML 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 PS。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EML 转换为 PS" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EML 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 PS 格式，并将 Ps 设置为 SaveFormat
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

document.Save("output.ps", SaveFormat.Ps); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EML 文件" %}}
在将 EML 转换为 PS 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EML 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/eml) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 PS 文档编辑" %}}
在将文档从 EML 保存到 PS 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EML 文件转换为 PS：用例" %}}
电子邮件文件（EML）用于存储纯文本信息，适合发送和接收格式要求较少的邮件。然而，在处理专业演示文稿和多媒体内容时，PS 文件变得至关重要。

将 EML 文件转换为 PS 格式是必要的，以充分发挥您的演示文稿创建和分享能力。这一转换使您能够：

**用途：**

*   **专业演示文稿制作**：将 EML 文件转换为包含文字、图片和多媒体内容的专业演示文稿。
*   **商务沟通**：使用 PS 格式发送定制化的商务演示文稿、报告和提案，展现高度的专业性。
*   **营销材料制作**：将 EML 文件转换为吸引人的营销材料，如销售推销、产品演示和会议演讲。
*   **教育培训**：使用 PS 格式创建交互式教育内容，包括演示文稿幻灯片、多媒体课程和教练指南。
*   **内部沟通**：将 EML 文件转换为发送公司内通信的文件，如政策更新、会议总结和团队公告。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}