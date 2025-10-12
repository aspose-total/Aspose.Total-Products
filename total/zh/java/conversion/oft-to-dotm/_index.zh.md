---
title: 通过 Java 将 OFT 导出为 DOTM
description: 无需使用 Microsoft Word 或 Outlook 即可将 OFT 转换为 DOTM 的 Java API
url_ignore: /zh/java/conversion/oft-to-dotm/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOTM
otherformats: MD DOCM PS GIF XPS DOC DOT ODT DOTM EMF OTT DOTX SVG TEXT WORDML DOCX RTF PNG TIFF FLATOPC PDF EPUB JPEG PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 OFT 渲染为 DOTM 的 Java API" h2="使用本地 Java API 将 OFT 导出到 DOTM，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 OFT 转换为 DOTM，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Oft for Java](https://products.aspose.com/email/java/) 将 OFT 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 DOTM。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 OFT 转换为 DOTM" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 OFT 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) 将 OFT 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 DOTM 格式)) 方法并将 DOTM 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/agp/feature-section >}}

将 **OFT 转换为 DOTM** 可生成 **支持宏的 Word 模板**，从转换的 Outlook 模板生成新文档时实现自动化和动态字段更新。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* 将宏嵌入企业通信模板
* 自动化重复的文档生成任务
* 从基于电子邮件的模板个性化信函或表格
* 在 Word 模板生成中强制执行工作流规则
* 使用 VBA 脚本进行高级定制

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 使用预定义宏自动进行 OFT 到 DOTM 的转换
* 与 CRM 或 ERP 系统集成以实现文档自动化
* 从外部数据源动态插入字段
* 带有宏逻辑的工作流触发的文档创建
* 企业自动化标准化文档集

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}