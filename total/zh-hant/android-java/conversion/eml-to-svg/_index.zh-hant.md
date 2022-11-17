---
title: 在 Andorid App 中將 EML 渲染為 SVG
description: 在您的 Andorid 應用程序中不使用 Microsoft Word 或 Outlook 將 EML 導出為 SVG

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: SVG
otherformats: BMP DOT TEXT XPS DOTX EPUB PCL RTF DOTM JPEG FLATOPC WORDML OTT ODT PDF PS PNG DOC DOCM DOCX EMF TIFF MD GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Andorid 應用程序中將 EML 轉換為 SVG" h2="設計 Andorid 應用程序以通過 Java API 使用 Andorid 將 EML 導出到 SVG" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 應用程序易於終端用戶日常使用。 Andorid 手機用戶的數量每天都在增加。使用強大的 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 文件格式自動化庫，您可以開發電子郵件處理和轉換應用程序。您可以通過 [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) 和 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。使用第一個 API，您可以將 EML 文件格式轉換為 HTML，通過使用第二個 API，您可以將 HTML 呈現為 SVG。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Andorid 中將 EML 轉換為 SVG" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) 類打開 EML 文件
2. 使用 [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) 將 EML 轉換為 HTML )) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 類加載 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 將文檔保存為 SVG 格式)) 方法並將 SVG 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Eml for Android](https://docs.aspose.com/eml/androidjava/installation/) 和 [Aspose.Words for Andorid 通過 Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.SVG
document.save("output.svg", SaveFormat.SVG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-svg/" name="EML 至 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-dot/" name="EML 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-text/" name="EML 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-xps/" name="EML 至 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-dotx/" name="EML 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-epub/" name="EML 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-pcl/" name="EML 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-rtf/" name="EML 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-dotm/" name="EML 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-jpeg/" name="EML 至 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-flatopc/" name="EML 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-wordml/" name="EML 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-ott/" name="EML 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-odt/" name="EML 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-pdf/" name="EML 至 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-ps/" name="EML 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-png/" name="EML 至 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-doc/" name="EML 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-docm/" name="EML 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-docx/" name="EML 至 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-emf/" name="EML 至 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-tiff/" name="EML 至 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-md/" name="EML 至 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/eml-to-gif/" name="EML 至 GIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}