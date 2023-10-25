---
title: 在 Andorid App 中將 MSG 渲染為 DOT
description: 在您的 Andorid 應用程序中不使用 Microsoft Word 或 Outlook 將 MSG 導出為 DOT

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOT
otherformats: TIFF PDF DOCX TEXT WORDML SVG DOC GIF DOTX BMP DOTM EMF EPUB PS FLATOPC PNG RTF OTT PCL JPEG DOCM MD ODT XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Andorid 應用程序中將 MSG 轉換為 DOT" h2="設計 Andorid 應用程序以通過 Java API 使用 Andorid 將 MSG 導出到 DOT" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid 應用程序易於終端用戶日常使用。 Andorid 手機用戶的數量每天都在增加。使用強大的 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 文件格式自動化庫，您可以開發電子郵件處理和轉換應用程序。您可以通過 [Aspose.Msg for Android Java](https://products.aspose.com/msg/android-java/) 和 [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。使用第一個 API，您可以將 MSG 文件格式轉換為 HTML，通過使用第二個 API，您可以將 HTML 呈現為 DOT。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Andorid 中將 MSG 轉換為 DOT" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) 類打開 MSG 文件
2. 使用 [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) 將 MSG 轉換為 HTML )) 方法
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 類加載 HTML
4. 使用 [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 將文檔保存為 DOT 格式)) 方法並將 DOT 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://releases.aspose.com/total/java/)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.Msg for Android](https://docs.aspose.com/msg/androidjava/installation/) 和 [Aspose.Words for Andorid 通過 Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://releases.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}