---
title: 通过 Java 将 EML 导出为 DOCX
description: 无需使用 Microsoft Word 或 Outlook 即可将 EML 转换为 DOCX 的 Java API
url_ignore: /zh/java/conversion/eml-to-docx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: MD PDF GIF EPUB SVG PNG ODT XPS OTT DOC TEXT DOCX DOTX RTF PS TIFF DOT EMF FLATOPC WORDML DOTM DOCM JPEG PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EML 渲染为 DOCX 的 Java API" h2="使用本地 Java API 将 EML 导出到 DOCX，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EML 转换为 DOCX，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EML 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 DOCX。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EML 转换为 DOCX" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) 将 EML 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 DOCX 格式)) 方法并将 DOCX 设置为 SaveFormat
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
将 **EML 转换为 DOCX** 可使电子邮件数据以现代、广泛使用的 Microsoft Word 格式可供编辑、协作和数字存储。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

* 将电子邮件转换为可重复使用的业务文件
* 以 Word 格式共享与项目相关的沟通
* 从电子邮件线程生成格式化报告
* 为演示或会议准备文档

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 用于企业报告的自动化电子邮件至 Word 流程
* 将整个邮箱转换为 DOCX 进行归档
* 与 CRM/ERP 系统集成以生成文档
* 用于项目文档化的工作流自动化
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}