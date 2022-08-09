---
title: 在 Andorid App 中将 EML 渲染为 IMAGE
description: 在您的 Andorid 应用程序中不使用 Microsoft Word 或 Outlook 将 EML 导出为 IMAGE
url: /zh/android-java/conversion/eml-to-image/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: MD DOTX OTT FLATOPC DOCM ODT DOTM TIFF PNG DOT DOCX PCL XPS EPUB GIF SVG DOC BMP JPEG WORDML PS PDF RTF EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Andorid 应用程序中将 EML 转换为 IMAGE" h2="设计 Andorid 应用程序以通过 Java API 使用 Andorid 将 EML 导出到 IMAGE" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 应用程序易于终端用户日常使用。 Andorid 手机用户的数量每天都在增加。使用强大的 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 文件格式自动化库，您可以开发电子邮件处理和转换应用程序。您可以通过 [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) 和 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。使用第一个 API，您可以将 EML 文件格式转换为 HTML，通过使用第二个 API，您可以将 HTML 呈现为 IMAGE。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Andorid 中将 EML 转换为 IMAGE" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 类打开 EML 文件
2. 使用 [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) 将 EML 转换为 HTML )) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document)) 将文档保存为 IMAGE 格式)) 方法并将 IMAGE 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和通过 Java 安装 [Aspose.Eml for Android](https://docs.aspose.com/eml/androidjava/installation/) 和 [Aspose.Words for Andorid 通过 Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://downloads.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-md/" name="EML 至 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-dotx/" name="EML 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-ott/" name="EML 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-flatopc/" name="EML 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-docm/" name="EML 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-odt/" name="EML 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-dotm/" name="EML 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-tiff/" name="EML 至 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-png/" name="EML 至 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-dot/" name="EML 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-docx/" name="EML 至 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-pcl/" name="EML 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-xps/" name="EML 至 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-epub/" name="EML 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-gif/" name="EML 至 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-svg/" name="EML 至 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-doc/" name="EML 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-image/" name="EML 至 IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-jpeg/" name="EML 至 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-wordml/" name="EML 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-ps/" name="EML 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-pdf/" name="EML 至 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-rtf/" name="EML 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/eml-to-emf/" name="EML 至 EMF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}