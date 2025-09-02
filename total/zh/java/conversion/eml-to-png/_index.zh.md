---
title: 通过 Java 将 EML 导出为 PNG
description: 无需使用 Microsoft Word 或 Outlook 即可将 EML 转换为 PNG 的 Java API
url_ignore: /zh/java/conversion/eml-to-png/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: DOTM DOT PDF ODT EPUB SVG DOTX TEXT PS RTF XPS WORDML PNG EMF JPEG GIF TIFF DOCX FLATOPC DOCM MD DOC OTT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EML 渲染为 PNG 的 Java API" h2="使用本地 Java API 将 EML 导出到 PNG，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EML 转换为 PNG，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EML 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 PNG。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EML 转换为 PNG" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) 将 EML 转换为 HTML)) 方法
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
将 **EML** 转换为 **PNG（便携式网络图形）** 可确保以高质量、无损的视觉形式呈现电子邮件。  

## ✅ 主要用途  
- **高保真存档**：以像素级准确性保存电子邮件细节。  
- **透明背景**：保存带透明度的电子邮件以供设计使用。  
- **培训内容**：将电子邮件图像插入用户指南或手册中。  
- **网络集成**：在网站或内部门户网站上发布电子邮件视觉内容。  

## ⚙️ 自动化场景  
- **批量 PNG 转换**：将多个 EML 导出为高分辨率 PNG。  
- **合规记录**：保留业务沟通的不可变快照。  
- **知识管理**：将 PNG 快照插入维基和文档中。  
- **电子邮件预览**：在工单/帮助台系统中生成自动预览。  
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}