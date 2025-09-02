---
title: 通过 Java 将 MSG 导出为 PNG
description: 无需使用 Microsoft Word 或 Outlook 即可将 MSG 转换为 PNG 的 Java API
url_ignore: /zh/java/conversion/msg-to-png/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOTX TIFF PNG OTT DOTM PS DOC EPUB WORDML SVG PDF DOCM MD XPS RTF DOT FLATOPC PCL JPEG ODT DOCX EMF GIF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 MSG 渲染为 PNG 的 Java API" h2="使用本地 Java API 将 MSG 导出到 PNG，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 MSG 转换为 PNG，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 MSG 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 PNG。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 MSG 转换为 PNG" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 MSG 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) 将 MSG 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 PNG 格式)) 方法并将 PNG 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
```
将 **MSG 转换为 PNG** 可生成保持高视觉质量的无损电子邮件快照，非常适用于文档和合规性。

## ✅ 主要用例

* 使用无损图像质量存档电子邮件。
* 需要确切保存电子邮件的法律和合规性案例。
* 将电子邮件视觉内容嵌入高分辨率数字文档。
* 支持需要保真度的法证调查。

## ⚙️ 自动化场景

* 面向合规性驱动的电子邮件保留的自动化 MSG 到 PNG 管道。
* 以高质量 PNG 格式存储电子邮件的企业存档工作流程。
* 支持 PNG 输出的多格式备份解决方案。
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}