---
title: 通过 Java 将 EML 导出为 DOT
description: 无需使用 Microsoft Word 或 Outlook 即可将 EML 转换为 DOT 的 Java API
url_ignore: /zh/java/conversion/eml-to-dot/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOT
otherformats: PDF DOTX SVG RTF ODT DOC FLATOPC DOT WORDML DOCM XPS PS DOTM PNG TIFF OTT EPUB MD TEXT DOCX GIF EMF PCL JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EML 渲染为 DOT 的 Java API" h2="使用本地 Java API 将 EML 导出到 DOT，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EML 转换为 DOT，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EML 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 DOT。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EML 转换为 DOT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) 将 EML 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 DOT 格式)) 方法并将 DOT 设置为 SaveFormat
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
将 **EML 转换为 DOT** 可以将电子邮件转换为可重复使用的 Word 模板，有助于基于电子邮件内容创建结构化文档格式。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

* 从客户沟通创建标准模板
* 将重复的电子邮件转换为预先设计的文档布局
* 将电子邮件内容作为品牌报告的基础
* 从电子邮件文本准备法律或公司模板

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 从客户请求自动生成文档模板
* 基于模板的报告系统
* 标准化项目沟通格式
* 用于企业工作流程的电子邮件到模板管道
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}