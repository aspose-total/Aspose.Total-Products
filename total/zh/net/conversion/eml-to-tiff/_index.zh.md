---
title: 将 EML 导出为 TIFF 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EML 转换为 TIFF
url_ignore: /zh/net/conversion/eml-to-tiff/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TIFF
otherformats: TIFF GIF XPS DOTX SVG ODT PCL DOCM PDF DOC PS RTF MD EPUB PNG FLATOPC DOTM DOCX EMF WORDML JPEG OTT DOT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EML 导出到 TIFF" h2=".NET API 在 Windows、macOS 和 Linux 上将 EML 渲染为 TIFF，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EML 到 TIFF 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EML 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 TIFF。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EML 转换为 TIFF" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EML 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 TIFF 格式，并将 Tiff 设置为 SaveFormat
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
在将 EML 转换为 TIFF 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EML 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/eml) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 TIFF 文档编辑" %}}
在将文档从 EML 保存到 TIFF 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EML 文件转换为 TIFF：用例" %}}
电子邮件文件（EML）用于存储基于文本的消息，因此它们是发送和接收电子邮件的理想格式。然而，当处理图像数据时，TIFF（标签化图像文件格式）等格式变得至关重要，以实现高质量图像的保存与操作。

将 EML 文件转换为 TIFF 格式是必要的，以充分发挥您的图像数据能力。这一转换使您能够：

**用途：**

*   **医疗影像分析**：将 EML 文件转换为 TIFF 格式以分析医疗影像，追踪患者进展并识别数据中的模式。
*   **存档与保存**：使用 TIFF 格式来保存高质量图像，以便于档案保存，并确保数字副本在未来长期内保持稳定。
*   **图像编辑与增强**：将 EML 文件转换为 TIFF 格式以创建和编辑图像，应用滤镜、调整和效果以获得预期结果。
*   **科学影像处理**：使用 TIFF 格式来处理科学影像，执行图像配准并提高图像质量以进行进一步分析。
*   **数字forensics调查**：将 EML 文件转换为 TIFF 格式以分析数字证据，追踪在线活动并重建数字事件。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}