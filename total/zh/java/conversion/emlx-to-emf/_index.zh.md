---
title: 通过 Java 将 EMLX 导出为 EMF
description: 无需使用 Microsoft Word 或 Outlook 即可将 EMLX 转换为 EMF 的 Java API
url_ignore: /zh/java/conversion/emlx-to-emf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EMF
otherformats: DOCX JPEG TIFF PDF DOCM TEXT RTF PNG DOT PCL SVG EPUB WORDML DOTM FLATOPC MD DOC OTT ODT EMF DOTX PS XPS GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EMLX 渲染为 EMF 的 Java API" h2="使用本地 Java API 将 EMLX 导出到 EMF，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EMLX 转换为 EMF，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EMLX 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 EMF。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EMLX 转换为 EMF" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 EMLX 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) 将 EMLX 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 EMF 格式)) 方法并将 EMF 设置为 SaveFormat
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
将EMLX（Apple Mail电子邮件文件）转换为**EMF（增强型图元文件格式）**，可以精确地呈现电子邮件布局，包括字体、图像和格式，以便在基于Windows的应用程序中使用。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}
- 将Apple Mail电子邮件存档为可缩放矢量图像。
- 保留通讯和促销电子邮件的视觉保真度。
- 将电子邮件整合到Windows报告和文档中。
- 确保分辨率独立的打印就绪输出。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- 将EMLX存档批量转换为EMF以用于数字记录。
- 用于法律/合规电子邮件证据存储的自动化流程。
- 与使用EMF图形的报告系统集成的工作流程。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}