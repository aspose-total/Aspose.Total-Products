---
title: 通过 Java 将 EMAIL 导出为 TEXT
description: 无需使用 Microsoft Word 或 Outlook 即可将 EMAIL 转换为 TEXT 的 Java API
url_ignore: /zh/java/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: DOT PS SVG PDF XPS FLATOPC WORDML JPEG DOCM PCL DOCX RTF GIF TIFF PNG EPUB TEXT MD OTT DOC ODT DOTM DOTX EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EMAIL 渲染为 TEXT 的 Java API" h2="使用本地 Java API 将 EMAIL 导出到 TEXT，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EMAIL 转换为 TEXT，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EMAIL 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 TEXT。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EMAIL 转换为 TEXT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 EMAIL 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) 将 EMAIL 转换为 HTML 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 TEXT 格式)) 方法并将 TEXT 设置为 SaveFormat
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
将电子邮件转换为**纯文本（.txt）**可确保以最简单、最便携的形式提取消息的基本内容。该格式剥离了不必要的格式，使数据变得轻巧、可搜索，并且在各个平台上具有高度兼容性。  


{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}  
- **存档与合规性**：以文本形式存储电子邮件，用于轻量级、长期存档。  
- **电子发现与法律**：仅提取原始文本以用于调查或诉讼支持。  
- **数据挖掘与分析**：准备非结构化电子邮件文本以用于自然语言处理、人工智能或搜索索引。  
- **迁移至传统系统**：以通用接受的文本格式提供电子邮件内容。  
- **离线访问**：在不支持丰富格式的设备或应用上阅读电子邮件。  


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}  
- **批量导出**：将成千上万封电子邮件转换为`.txt`以进行存储或分析流程。  
- **内容提取**：自动化工作流程以剥离元数据、HTML和签名，仅保留干净的文本。  
- **搜索引擎索引**：创建自动化的`.txt`输出以构建可搜索的存档。  
- **电子邮件解析流水线**：将`.txt`输出用作结构化数据提取的中间格式。  
- **合规性自动化**：从收发电子邮件中自动生成纯文本日志。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}