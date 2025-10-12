---
title: 通过 Java 将 OFT 导出为 PDF
description: 无需使用 Microsoft Word 或 Outlook 即可将 OFT 转换为 PDF 的 Java API
url_ignore: /zh/java/conversion/oft-to-pdf/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PDF
otherformats: TIFF RTF PCL FLATOPC DOCX DOCM DOTM XPS PNG EPUB SVG DOT TEXT GIF JPEG DOC ODT WORDML PS EMF PDF MD DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 OFT 渲染为 PDF 的 Java API" h2="使用本地 Java API 将 OFT 导出到 PDF，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 OFT 转换为 PDF，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Oft for Java](https://products.aspose.com/email/java/) 将 OFT 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 PDF。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 OFT 转换为 PDF" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 OFT 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) 将 OFT 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 PDF 格式)) 方法并将 PDF 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-pdf.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/agp/feature-section >}}

将 **OFT 转换为 PDF** 可将 Outlook 模板转换为 **便携文档格式文件**，实现安全、固定布局的共享、打印和存档电子邮件设计，无需 Microsoft Outlook。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* 将电子邮件模板分发为通用可查看的 PDF 文件
* 存档 Outlook 模板以符合合规性和记录保存要求
* 打印具有一致格式的标准化电子邮件布局
* 与外部合作伙伴共享企业通信
* 从 OFT 模板生成报告或文档

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 用于企业分发的自动化 OFT 到 PDF 转换
* 与文档管理和存档系统集成
* 批量处理模板以进行打印或报告
* 安全的只读共享企业电子邮件设计
* 从 OFT 模板生成 PDF 库以便轻松访问

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}