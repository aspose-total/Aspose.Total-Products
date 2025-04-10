---
title: 将 EMAIL 导出为 JPEG 的 C# API
description: 在 .NET 上不使用 Microsoft Word 或 Outlook 将 EMAIL 转换为 JPEG
url_ignore: /zh/net/conversion/email-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PNG DOC DOT EMF FLATOPC ODT MD TIFF XPS DOCM EPUB TEXT WORDML JPEG DOTM OTT PDF SVG DOCX GIF RTF PCL PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 .NET 将 EMAIL 导出到 JPEG" h2=".NET API 在 Windows、macOS 和 Linux 上将 EMAIL 渲染为 JPEG，而无需使用 Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
如果您是一名 .NET 开发人员，希望在您的应用程序中添加 EMAIL 到 JPEG 转换功能，那么 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 文件格式操作 API 是一种方式向前。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email/net/)，您可以将 EMAIL 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for .NET](https://products.aspose.com/words/net/)，您可以将 HTML 渲染为 JPEG。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API 将 EMAIL 转换为 JPEG" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 类打开 EMAIL 文件
2. 使用 [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 方法将 EMAIL 转换为 HTML
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

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 解析 EMAIL 文件" %}}
在将 EMAIL 转换为 JPEG 之前，如果您想确保您正在转换正确的电子邮件，您可以加载 EMAIL 文档，对其进行解析并查看您想要的属性。通过使用 [Aspose.Email for .NET](https://products.aspose.com/email) 的 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 类/net/) API，可以获取发件人和收件人信息。例如，您可以使用 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 属性检查转换的特定发件人电子邮件。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 .NET 限制 JPEG 文档编辑" %}}
在将文档从 EMAIL 保存到 JPEG 时，您可能需要保护您的输出文档。有时您可能需要限制编辑文档的能力，只允许对其进行某些操作。这对于防止其他人编辑您文档中的敏感和机密信息很有用。 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API，使您能够使用 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 枚举参数。您可以使用以下代码行将文档设置为只读。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 EMAIL 文件转换为 JPEG：用例" %}}
将电子邮件文件转换为JPEG图片，是解锁视觉潜力的必要手段。

电子邮件文件，包含重要的通信数据，在转换为JPEG图片后，成为静态视觉呈现和分享的理想选择。然而，当处理动态内容时，社交媒体平台如Instagram就变得至关重要，以实现视觉叙事和互动。

将电子邮件文件转换为JPEG格式，是为了充分发挥您的视觉内容和可共享性的潜力。这一转换使您能够：

**用途：**

* **社交媒体分享**：将电子邮件文件转换为可以在各大社交平台上分享的吸引人的JPEG图片，以触达更广泛的受众。
* **电商产品视觉化**：使用JPEG图片展示产品细节、规格和功能，提升在线购物体验。
* **活动推广与广告**：将电子邮件文件转换为JPEG图片来促销活动、产品或服务，以吸引注意力并激发兴趣。
* **信息图表与数据可视化**：利用JPEG图片来可视化数据、统计和信息，制作出有趣且富有教育意义的内容以满足各类受众需求。
* **数字营销活动**：将电子邮件文件转换为JPEG图片创建引人注目的视觉元素，以制定吸引眼球的广告牌和促销材料。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}