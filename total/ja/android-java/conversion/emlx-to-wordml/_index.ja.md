---
title: AndoridアプリでメールをWORDMLにレンダリングする
description: AndoridアプリケーションでMicrosoftWordまたはOutlookを使用せずにEMLXをWORDMLにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: WORD_ML
otherformats: SVG TIFF OTT PDF DOT MD XPS DOCM TEXT DOC ODT EMF PCL DOTM EPUB DOTX RTF GIF PNG PS DOCX BMP JPEG FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndoridアプリでメールをWORDMLに変換する" h2="JavaAPIを介してAndoridを使用してEMLXをWORDMLにエクスポートするためのAndoridアプリケーションの設計" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Appsは、日常的にエンドユーザーにとって使いやすいものです。 Andorid電話のユーザー数は日々増加しています。強力な[Aspose.TotalforAndroid via Java](https://products.aspose.com/total/android-java/)ファイル形式自動化ライブラリを使用して、電子メール操作および変換アプリケーションを開発できます。 [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/)と[Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/)。最初のAPIを使用すると、EMLXファイル形式をHTMLに変換でき、2番目のAPIを使用すると、HTMLをWORDMLとしてレンダリングできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndoridでEMLXをWORDMLに変換する" %}}
1. [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)を使用して、EMLXをHTMLに変換します。 )) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをWORDML形式で保存します))メソッドとWORDMLをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Emlx for Android via Java](https://docs.aspose.com/emlx/androidjava/installation/)と[Aspose.Words for Andorid via Java](https://docs.aspose.com/words)をインストールします。アプリケーションの/java/ install-aspose-words-for-android-via-java /＃install-asposewords-for-android-via-java-from-maven-repository)。

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
// call save method while passing SaveFormat.WORD_ML
document.save("output.word_ml", SaveFormat.WORD_ML); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-svg/" name="EMLX に SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-tiff/" name="EMLX に TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-ott/" name="EMLX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-pdf/" name="EMLX に PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-dot/" name="EMLX に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-md/" name="EMLX に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-xps/" name="EMLX に XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-docm/" name="EMLX に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-text/" name="EMLX に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-doc/" name="EMLX に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-odt/" name="EMLX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-emf/" name="EMLX に EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-pcl/" name="EMLX に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-dotm/" name="EMLX に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-epub/" name="EMLX に EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-dotx/" name="EMLX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-rtf/" name="EMLX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-gif/" name="EMLX に GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-png/" name="EMLX に PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-ps/" name="EMLX に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-docx/" name="EMLX に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-wordml/" name="EMLX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-jpeg/" name="EMLX に JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/emlx-to-flatopc/" name="EMLX に FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}