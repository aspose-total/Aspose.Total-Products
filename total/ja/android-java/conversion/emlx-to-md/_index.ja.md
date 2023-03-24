---
title: AndoridアプリでメールをMDにレンダリングする
description: AndoridアプリケーションでMicrosoftWordまたはOutlookを使用せずにEMLXをMDにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: MD
otherformats: DOTX OTT DOCX PDF JPEG EMF PS DOT EPUB XPS ODT DOC GIF PNG PCL TEXT TIFF DOCM DOTM FLATOPC SVG BMP RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndoridアプリでメールをMDに変換する" h2="JavaAPIを介してAndoridを使用してEMLXをMDにエクスポートするためのAndoridアプリケーションの設計" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Appsは、日常的にエンドユーザーにとって使いやすいものです。 Andorid電話のユーザー数は日々増加しています。強力な[Aspose.TotalforAndroid via Java](https://products.aspose.com/total/android-java/)ファイル形式自動化ライブラリを使用して、電子メール操作および変換アプリケーションを開発できます。 [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/)と[Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。最初のAPIを使用すると、EMLXファイル形式をHTMLに変換でき、2番目のAPIを使用すると、HTMLをMDとしてレンダリングできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndoridでEMLXをMDに変換する" %}}
1. [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)を使用して、EMLXをHTMLに変換します。 )) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをMD形式で保存します))メソッドとMDをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Emlx for Android via Java](https://docs.aspose.com/emlx/androidjava/installation/)と[Aspose.Words for Andorid via Java](https://docs.aspose.com/words)をインストールします。アプリケーションの/java/ install-aspose-words-for-android-via-java /＃install-asposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
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
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}