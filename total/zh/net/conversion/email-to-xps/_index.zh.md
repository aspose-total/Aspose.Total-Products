---
title: 将 EMAIL 导出为 XPS 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMAIL 转换为 XPS
url_ignore: /zh/net/conversion/email-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: ODT DOTM DOCX PDF JPEG TEXT DOCM WORDML RTF PS PNG TIFF DOTX EMF XPS GIF MD DOC OTT DOT SVG PCL EPUB FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMAIL 导出到 XPS" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMAIL 渲染为 XPS，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMAIL 到 XPS 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMAIL 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 XPS。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMAIL 转换为 XPS" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMAIL 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMAIL 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 XPS 格式，并将 Xps 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMAIL 文件" %}}
在将 EMAIL 转换为 XPS 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMAIL 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 XPS 文档编辑" %}}
在将文档从 EMAIL 保存到 XPS 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMAIL 文件转换为 XPS：用例" %}}
将电子邮件转换为XPS文件：解锁视觉内容的潜力。

电子邮件是沟通的重要工具，但在视觉内容方面，它们往往不尽如人意。与其他格式（如PDF或XPS）不同，电子邮件在传输过程中可能会降低图像质量和格式。因此，转换成为关键。

将电子邮件转换为XPS文件是一个简单的过程，可以实现以下目的：

**用途：**

*   **视觉内容保留**: 将电子邮件转换为XPS文件以确保您的视觉内容在分享或存档时保持完整。
*   **打印友好沟通**: 使用XPS文件创建适合演示、报告和其他正式沟通的打印版本。
*   **安全与合规**: 将电子邮件转换为XPS文件以满足法规要求并确保敏感视觉内容的安全性。
*   **存档与保留**: 存储XPS文件以保存电子邮件附件和图像，以供未来参考或符合目的。
*   **可访问性与包容性**: 将电子邮件转换为XPS文件以提高可访问性，为视力障碍者提供替代格式。

通过将您的电子邮件转换为XPS文件，您可以解锁视觉内容的全部潜力，并确保其保持鲜艳完整。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}