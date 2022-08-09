---
title: 在 Andorid App 中将 EMAIL 渲染为 PDF
description: 在您的 Andorid 应用程序中不使用 Microsoft Word 或 Outlook 将 EMAIL 导出为 PDF
url: /zh/android-java/conversion/email-to-pdf/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PDF
otherformats: RTF EMF DOCX TEXT DOC PNG FLATOPC DOCM WORDML ODT JPEG PS GIF BMP DOT OTT DOTM XPS TIFF PCL MD EPUB DOTX SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Andorid 应用程序中将 EMAIL 转换为 PDF" h2="设计 Andorid 应用程序以通过 Java API 使用 Andorid 将 EMAIL 导出到 PDF" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 应用程序易于终端用户日常使用。 Andorid 手机用户的数量每天都在增加。使用强大的 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 文件格式自动化库，您可以开发电子邮件处理和转换应用程序。您可以通过 [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) 和 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。使用第一个 API，您可以将 EMAIL 文件格式转换为 HTML，通过使用第二个 API，您可以将 HTML 呈现为 PDF。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Andorid 中将 EMAIL 转换为 PDF" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 类打开 EMAIL 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage) 将 EMAIL 转换为 HTML )) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document)) 将文档保存为 PDF 格式)) 方法并将 PDF 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和通过 Java 安装 [Aspose.Email for Android](https://docs.aspose.com/email/androidjava/installation/) 和 [Aspose.Words for Andorid 通过 Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://downloads.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PDF
document.save("output.pdf", SaveFormat.PDF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-rtf/" name="MSG 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-emf/" name="MSG 至 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-docx/" name="MSG 至 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-text/" name="MSG 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-doc/" name="MSG 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-png/" name="MSG 至 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-flatopc/" name="MSG 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-docm/" name="MSG 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-wordml/" name="MSG 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-odt/" name="MSG 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-jpeg/" name="MSG 至 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-ps/" name="MSG 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-gif/" name="MSG 至 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-pdf/" name="MSG 至 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-dot/" name="MSG 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-ott/" name="MSG 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-dotm/" name="MSG 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-xps/" name="MSG 至 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-tiff/" name="MSG 至 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-pcl/" name="MSG 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-md/" name="MSG 至 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-epub/" name="MSG 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-dotx/" name="MSG 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/msg-to-svg/" name="MSG 至 SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}