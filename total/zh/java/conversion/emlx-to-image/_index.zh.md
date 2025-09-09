---
title: 通过 Java 将 EMLX 导出为 IMAGE
description: 无需使用 Microsoft Word 或 Outlook 即可将 EMLX 转换为 IMAGE 的 Java API
url_ignore: /zh/java/conversion/emlx-to-image/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: DOT EMF MD DOCX EPUB IMAGE PCL XPS DOC RTF GIF TEXT FLATOPC JPEG DOTX PNG SVG DOTM OTT ODT TIFF WORDML DOCM PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EMLX 渲染为 IMAGE 的 Java API" h2="使用本地 Java API 将 EMLX 导出到 IMAGE，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EMLX 转换为 IMAGE，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EMLX 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 IMAGE。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EMLX 转换为 IMAGE" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 EMLX 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) 将 EMLX 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 IMAGE 格式)) 方法并将 IMAGE 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/feature-section >}}
```
将**EMLX（Apple Mail电子邮件文件）**转换为通用的**图像格式**可确保与各种系统兼容，为电子邮件的存档和视觉共享提供灵活的方法。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

- **通用查看** → 确保电子邮件内容在任何设备或系统上都可以以图像形式查看。
- **存档与存储** → 转换为图像格式以进行长期存储和备份。
- **法律与合规** → 以图像格式保留电子邮件以保持完整性。
- **发布** → 将电子邮件内容插入文档、演示文稿或在线门户。
- **安全共享** → 将消息以静态图像形式分发，而不是可编辑文本。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **通用EMLX到图像管道** → 自动将其转换为系统兼容的图像文件。
- **企业工作流程** → 将电子邮件转换为图像并整合到合规和报告系统中。
- **电子邮件到发布管道** → 自动将传入的电子邮件转换为内容工作流程。
- **多格式支持** → 提供图像导出以满足BMP、JPEG、PNG或TIFF的要求。
- **安全存档** → 将敏感消息保存为不可更改的图像格式。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}