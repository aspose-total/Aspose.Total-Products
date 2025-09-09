---
title: 通过 Java 将 EML 导出为 BMP
description: 无需使用 Microsoft Word 或 Outlook 即可将 EML 转换为 BMP 的 Java API
url_ignore: /zh/java/conversion/eml-to-bmp/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: BMP
otherformats: MD SVG EMF WORDML TEXT PS TIFF DOT PCL DOC FLATOPC DOCX DOCM DOTM ODT PDF GIF OTT EPUB DOTX XPS JPEG PNG RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="将 EML 渲染为 BMP 的 Java API" h2="使用本地 Java API 将 EML 导出到 BMP，而不使用任何第三方依赖项" >}}
{{% blocks/products/pf/feature-page-summary %}}
电子邮件转换是一项强大的功能，Java 开发人员可以通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将其集成到任何 Java J2SE、J2EE、J2ME 应用程序中。通过使用包中的两个 API，您可以将电子邮件 EML 转换为 BMP，而无需任何第三方依赖项。首先，您可以使用电子邮件操作 API [Aspose.Email for Java](https://products.aspose.com/email/java/) 将 EML 文件格式转换为 HTML。其次，您可以使用文档处理 API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 HTML 渲染为 BMP。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何将 EML 转换为 BMP" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) 将 EML 转换为 HTML)) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 BMP 格式)) 方法并将 BMP 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/feature-section >}}
```
将**EML（电子邮件消息格式）**文件转换为**BMP（位图图像）**可保留电子邮件的精确视觉布局，以静态、高质量的光栅格式呈现。


{{% blocks/products/pf/agp/feature-section-col title="主要用途" %}}
- **电子邮件存档**：存储电子邮件的不可编辑快照以备记录。
- **法律证据**：捕获电子邮件的原始外观以符合法规和法庭使用。
- **打印就绪文档**：将电子邮件转换为BMP，用于海报或实体记录。
- **图形设计**：在需要位图图像的设计工作流程中使用电子邮件内容。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **批量电子邮件快照**：将多个EML文件转换为BMP图像。
- **合规管道**：自动将所有企业电子邮件保存为位图形式。
- **取证存档**：将电子邮件保留为未更改的图像证据。
- **跨系统共享**：确保一致的查看，无需电子邮件客户端。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}