---
title: 在 Andorid App 中将 OFT 渲染为 MD
description: 在您的 Andorid 应用程序中不使用 Microsoft Word 或 Outlook 将 OFT 导出为 MD

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: MD
otherformats: PNG EPUB DOTX EMF GIF PS PCL XPS PDF RTF DOCX ODT SVG TEXT JPEG WORDML BMP DOCM DOT DOTM DOC FLATOPC TIFF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Andorid 应用程序中将 OFT 转换为 MD" h2="设计 Andorid 应用程序以通过 Java API 使用 Andorid 将 OFT 导出到 MD" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 应用程序易于终端用户日常使用。 Andorid 手机用户的数量每天都在增加。使用强大的 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 文件格式自动化库，您可以开发电子邮件处理和转换应用程序。您可以通过 [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) 和 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。使用第一个 API，您可以将 OFT 文件格式转换为 HTML，通过使用第二个 API，您可以将 HTML 呈现为 MD。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Andorid 中将 OFT 转换为 MD" %}}
1. 使用 [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage) 类打开 OFT 文件
2. 使用 [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) 将 OFT 转换为 HTML )) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document)) 将文档保存为 MD 格式)) 方法并将 MD 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://releases.aspose.com/total/java/)通过 Java 轻松使用 Aspose.Total for Android 和通过 Java 安装 [Aspose.Oft for Android](https://docs.aspose.com/oft/androidjava/installation/) 和 [Aspose.Words for Andorid 通过 Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://releases.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.MD
document.save("output.md", SaveFormat.MD); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}