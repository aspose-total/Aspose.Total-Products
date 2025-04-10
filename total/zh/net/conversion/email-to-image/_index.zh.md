---
title: 将 EMAIL 导出为 IMAGE 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMAIL 转换为 IMAGE
url_ignore: /zh/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMAIL 导出到 IMAGE" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMAIL 渲染为 IMAGE，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMAIL 到 IMAGE 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMAIL 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 IMAGE。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMAIL 转换为 IMAGE" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMAIL 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMAIL 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/net/aspose.words/document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 方法将文档保存为 IMAGE 格式，并将 Image 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMAIL 文件" %}}
在将 EMAIL 转换为 IMAGE 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMAIL 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 IMAGE 文档编辑" %}}
在将文档从 EMAIL 保存到 IMAGE 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.image", SaveFormat.Image);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMAIL 文件转换为 IMAGE：用例" %}}
**邮件到图像转换：解锁视觉叙事的潜力**

邮件是一种有效传达信息的手段，但与其他格式（如图像）相比，缺乏视觉吸引力。将邮件文件转换为图像格式是必要的，以解锁视觉叙事的全潜力，并保留内容以供未来参考。

将邮件文件转换为图像格式至关重要，以满足以下用途：

*   **内容保存**：将邮件转换为图像以捕捉内容，如会议笔记、销售协议或项目计划，并使其可供未来查阅。
*   **品牌保护**：使用图像转换来保留公司品牌、标志和其他视觉元素，从电子邮件中提取，以确保在所有通信渠道中的一致性。
*   **数字归档**：将邮件转换为图像以创建公司历史的数字归档，包括重要事件、里程碑和决策过程。
*   **可访问性与包容性**：将邮件转换为图像以使内容对视力有缺陷或残疾的人更易访问，使用替代文本描述提供上下文。
*   **安全与合规**：使用图像转换来保护敏感信息免受未经授权的访问，以满足监管机构对于数据保护和机密性的要求。

通过将邮件文件转换为图像格式，组织可以解锁视觉叙事的全潜力、保留内容，并确保符合法规。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}