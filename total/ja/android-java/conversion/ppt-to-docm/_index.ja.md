---
title: Java経由でAndoridのDOCMにPPTをエクスポートする
description: ソフトウェアをインストールせずにモバイルアプリでPPTをDOCMに変換する

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCM
otherformats: DOCX RTF ODT DOTM TEXT OTT DOC FLATOPC DOTX WORD WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndoridのDOCMにPPTをレンダリングする" h2="Microsoft PowerPointやWordに依存せずに、Androidアプリ内でPPTをDOCMに変換するファイル形式のAPI" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でファイル形式を操作できます。パッケージで提供されているAPIを使用することで、アプリでPowerPointPPTからWordDOCMへの変換プロセスを自動化できます。
あなたは2つのステップであなたの与えられた文書を変換することができます。 Androidアプリケーション用のPowerPointAPIである[Aspose.SlidesforAndorid via Java](https://products.aspose.com/slides/android-java/)を使用して、PPTをHTMLにレンダリングできます。その後、ドキュメント処理API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、HTMLをDOCMに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでのPPTからDOCMへのレンダリング" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)を使用してPPTをHTMLに変換します。ISaveOptions-)メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用して変換されたHTMLファイルをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをDOCM形式で保存し、Docmを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Slides for Android via Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/)と[Aspose.Words for Andorid viaJava]をインストールします（https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)アプリケーション。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document docmument = new Document("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-docmx/" name="PPT に DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-rtf/" name="PPT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-odt/" name="PPT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-dotm/" name="PPT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-text/" name="PPT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-ott/" name="PPT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-docm/" name="PPT に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-flatopc/" name="PPT に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-dotx/" name="PPT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-word/" name="PPT に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-wordml/" name="PPT に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/ppt-to-dot/" name="PPT に DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}