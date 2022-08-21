---
title: AndoridアプリでメールをDOTにレンダリングする
description: AndoridアプリケーションでMicrosoftWordまたはOutlookを使用せずにOFTをDOTにエクスポートする
url: /ja/android-java/conversion/oft-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOT
otherformats: DOTX OTT FLATOPC RTF DOCX ODT DOCM EPUB GIF DOC TIFF JPEG MD PDF BMP TEXT PS WORDML XPS PCL SVG PNG EMF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndoridアプリでメールをDOTに変換する" h2="JavaAPIを介してAndoridを使用してOFTをDOTにエクスポートするためのAndoridアプリケーションの設計" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Appsは、日常的にエンドユーザーにとって使いやすいものです。 Andorid電話のユーザー数は日々増加しています。強力な[Aspose.TotalforAndroid via Java](https://products.aspose.com/total/android-java/)ファイル形式自動化ライブラリを使用して、電子メール操作および変換アプリケーションを開発できます。 [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/)と[Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。最初のAPIを使用すると、OFTファイル形式をHTMLに変換でき、2番目のAPIを使用すると、HTMLをDOTとしてレンダリングできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndoridでOFTをDOTに変換する" %}}
1. [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)クラスを使用してOFTファイルを開きます
2. [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions)を使用して、OFTをHTMLに変換します。 )) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをDOT形式で保存します))メソッドとDOTをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Oft for Android via Java](https://docs.aspose.com/oft/androidjava/installation/)と[Aspose.Words for Andorid via Java](https://docs.aspose.com/words)をインストールします。アプリケーションの/java/ install-aspose-words-for-android-via-java /＃install-asposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-dotx/" name="OFT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-ott/" name="OFT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-flatopc/" name="OFT に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-rtf/" name="OFT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-docx/" name="OFT に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-odt/" name="OFT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-docm/" name="OFT に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-epub/" name="OFT に EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-gif/" name="OFT に GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-doc/" name="OFT に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-tiff/" name="OFT に TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-jpeg/" name="OFT に JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-md/" name="OFT に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-pdf/" name="OFT に PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-dot/" name="OFT に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-text/" name="OFT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-ps/" name="OFT に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-wordml/" name="OFT に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-xps/" name="OFT に XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-pcl/" name="OFT に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-svg/" name="OFT に SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-png/" name="OFT に PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-emf/" name="OFT に EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/oft-to-dotm/" name="OFT に DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}