---
title: 将 EMAIL 导出为 PDF 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMAIL 转换为 PDF
url_ignore: /zh/net/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: OTT DOT MD ODT TEXT PCL PS SVG DOCX DOTM DOCM JPEG RTF FLATOPC PNG XPS WORDML PDF EPUB DOC EMF DOTX TIFF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMAIL 导出到 PDF" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMAIL 渲染为 PDF，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMAIL 到 PDF 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMAIL 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 PDF。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMAIL 转换为 PDF" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMAIL 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMAIL 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 PDF 格式，并将 Pdf 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMAIL 文件" %}}
在将 EMAIL 转换为 PDF 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMAIL 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 PDF 文档编辑" %}}
在将文档从 EMAIL 保存到 PDF 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMAIL 文件转换为 PDF：用例" %}}
将电子邮件文件转换为PDF格式是必要的，以充分发挥您的文档管理能力。这种转换使您能够:

**用途:**

*   **正式记录和合规性**: 将电子邮件文件转换为PDF格式以维护正式记录，确保遵守法规，并促进审计。
*   **营销材料和推广活动**: 使用PDF转换创建印刷就绪的营销材料、手册和推广活动，以有效展示品牌形象。
*   **培训和教育内容**: 将电子邮件文件转换为PDF格式以创建交互式培训手册、课程材料和学习指南，供学生或员工使用。
*   **商业提案和合同**: 使用PDF转换创建专业的商业提案、合同和协议，以清晰且安全地传达您的信息。
*   **艺术创作和设计项目**: 将电子邮件文件转换为PDF格式以保存数字艺术作品、图像或设计，使其适合打印或与客户分享。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}