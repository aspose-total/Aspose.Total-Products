---
title: 在 Andorid App 中將 OFT 渲染為 BMP
description: 在您的 Andorid 應用程序中不使用 Microsoft Word 或 Outlook 將 OFT 導出為 BMP
url: /zh-hant/android-java/conversion/oft-to-bmp/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: BMP
otherformats: PS DOT OTT SVG GIF JPEG EMF DOC XPS ODT PDF TIFF FLATOPC DOTM PNG PCL MD EPUB TEXT DOCM DOCX DOTX WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Andorid 應用程序中將 OFT 轉換為 BMP" h2="設計 Andorid 應用程序以通過 Java API 使用 Andorid 將 OFT 導出到 BMP" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 應用程序易於終端用戶日常使用。 Andorid 手機用戶的數量每天都在增加。使用強大的 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 文件格式自動化庫，您可以開發電子郵件處理和轉換應用程序。您可以通過 [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) 和 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。使用第一個 API，您可以將 OFT 文件格式轉換為 HTML，通過使用第二個 API，您可以將 HTML 呈現為 BMP。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Andorid 中將 OFT 轉換為 BMP" %}}
1. 使用 [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage) 類打開 OFT 文件
2. 使用 [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) 將 OFT 轉換為 HTML )) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 類加載 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 將文檔保存為 BMP 格式)) 方法並將 BMP 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Oft for Android](https://docs.aspose.com/oft/androidjava/installation/) 和 [Aspose.Words for Andorid 通過 Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-ps/" name="OFT 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-dot/" name="OFT 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-ott/" name="OFT 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-svg/" name="OFT 至 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-gif/" name="OFT 至 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-jpeg/" name="OFT 至 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-emf/" name="OFT 至 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-doc/" name="OFT 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-xps/" name="OFT 至 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-odt/" name="OFT 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-pdf/" name="OFT 至 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-tiff/" name="OFT 至 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-flatopc/" name="OFT 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-dotm/" name="OFT 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-png/" name="OFT 至 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-pcl/" name="OFT 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-md/" name="OFT 至 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-epub/" name="OFT 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-text/" name="OFT 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-docm/" name="OFT 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-docx/" name="OFT 至 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-dotx/" name="OFT 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-wordml/" name="OFT 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/oft-to-rtf/" name="OFT 至 RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}