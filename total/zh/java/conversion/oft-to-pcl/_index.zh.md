---
title: 通过 Java 将 OFT 导出为 PCL
description: 无需使用 Microsoft Word 或 Outlook 即可将 OFT 转换为 PCL 的 Java API
url_ignore: /zh/java/conversion/oft-to-pcl/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PCL
otherformats: DOC MD EMF PCL ODT GIF PNG FLATOPC XPS DOT TEXT OTT TIFF SVG PS WORDML DOTM DOTX EPUB RTF DOCM PDF JPEG DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 OFT 渲染为 PCL 的 Java API" h2="使用本地 Java API 将 OFT 导出到 PCL，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 OFT 转换为 PCL，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Oft for Java](https://products.aspose.com/email/java/) 将 OFT 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 PCL。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 OFT 转换为 PCL" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 OFT 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) 将 OFT 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 PCL 格式)) 方法并将 PCL 设置为 SaveFormat
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

将 **OFT 转换为 PCL** 会生成 **打印机命令语言文件**，从而可以在兼容PCL打印机上直接打印Outlook模板，而无需Microsoft Office。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* 从公司打印机直接打印电子邮件模板
* 存档OFT模板的可打印版本
* 生成官方记录的标准化硬拷贝
* 确保多个打印设备上的模板一致性
* 预处理电子邮件以进行批量打印

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 用于打印工作流程的自动化OFT到PCL转换
* 与文档分发和打印系统集成
* 用于实体交付的公司模板的批处理处理
* 电子邮件模板的打印就绪内容管道
* 高容量打印任务的企业自动化

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}