---
title: Java経由でAndoridのRTFにPOTをエクスポートする
description: ソフトウェアをインストールせずにモバイルアプリでPOTをRTFに変換する

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: RTF
otherformats: DOTX FLATOPC DOC DOCX DOT DOCM OTT WORD DOTM TEXT ODT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndoridのRTFにPOTをレンダリングする" h2="Microsoft PowerPointやWordに依存せずに、Androidアプリ内でPOTをRTFに変換するファイル形式のAPI" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でファイル形式を操作できます。パッケージで提供されているAPIを使用することで、アプリでPowerPointPOTからWordRTFへの変換プロセスを自動化できます。
あなたは2つのステップであなたの与えられた文書を変換することができます。 Androidアプリケーション用のPowerPointAPIである[Aspose.SlidesforAndorid via Java](https://products.aspose.com/slides/android-java/)を使用して、POTをHTMLにレンダリングできます。その後、ドキュメント処理API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、HTMLをRTFに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでのPOTからRTFへのレンダリング" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPOTファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)を使用してPOTをHTMLに変換します。ISaveOptions-)メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)クラスを使用して変換されたHTMLファイルをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int))メソッドを使用してドキュメントをRTF形式で保存し、Rtfを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/)と[Aspose.Words for Andorid viaJava]をインストールします（https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)アプリケーション。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-dotx/" name="POT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-flatopc/" name="POT に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-rtf/" name="POT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-rtfx/" name="POT に RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-dot/" name="POT に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-rtfm/" name="POT に RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-ott/" name="POT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-word/" name="POT に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-dotm/" name="POT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-text/" name="POT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-odt/" name="POT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pot-to-wordml/" name="POT に WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}