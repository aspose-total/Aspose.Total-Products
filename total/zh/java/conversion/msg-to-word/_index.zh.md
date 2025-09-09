---
title: 通过 Java 将 MSG 导出为 WORD
description: 无需使用 Microsoft Word 或 Outlook 即可将 MSG 转换为 WORD 的 Java API
url_ignore: /zh/java/conversion/msg-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD
otherformats: WORD XPS TIFF DOTX MD PNG DOCX DOC PDF EPUB GIF TEXT PS RTF DOTM JPEG DOCM PCL EMF OTT WORDML DOT ODT SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 MSG 渲染为 WORD 的 Java API" h2="使用本地 Java API 将 MSG 导出到 WORD，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 MSG 转换为 WORD，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 MSG 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 WORD。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 MSG 转换为 WORD" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 MSG 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) 将 MSG 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 WORD 格式)) 方法并将 WORD 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/feature-section >}}
```
将 **MSG to WORD** 转换为将电子邮件文件转换为可编辑的 Microsoft Word 文档，结合了易用性和熟悉性。

#{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

* 将电子邮件交流转换为可编辑的报告
* 为审计准备通信日志
* 用于人力资源和合规目的的文档
* 从电子邮件准备法律案例

#{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 自动化的 MSG 到 Word 转换管道
* 将电子邮件存档到企业 Word 存储库
* 用于法律发现的批处理
* 人力资源报告工作流程
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}