---
title: Java経由でAndoridのDOCMにPPSをエクスポートする
description: ソフトウェアをインストールせずにモバイルアプリでPPSをDOCMに変換する
url: /ja/android-java/conversion/pps-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCM
otherformats: OTT DOTM FLATOPC DOT RTF DOC TEXT DOCX WORDML WORD DOTX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndoridのDOCMにPPSをレンダリングする" h2="Microsoft PowerPointやWordに依存せずに、Androidアプリ内でPPSをDOCMに変換するファイル形式のAPI" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java経由のAndroid用Aspose.Total](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でファイル形式を操作できます。パッケージで提供されているAPIを使用することで、アプリでPowerPointPPSからWordDOCMへの変換プロセスを自動化できます。
あなたは2つのステップであなたの与えられた文書を変換することができます。 Androidアプリケーション用のPowerPointAPIである[Aspose.SlidesforAndorid via Java](https://products.aspose.com/slides/android-java/)を使用して、PPSをHTMLにレンダリングできます。その後、ドキュメント処理API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、HTMLをDOCMに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでのPPSからDOCMへのレンダリング" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPSファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)を使用してPPSをHTMLに変換します。ISaveOptions-)メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument)クラスを使用して変換されたHTMLファイルをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,int))メソッドを使用してドキュメントをDOCM形式で保存し、Docmを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Slides for Android via Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/)と[Aspose.Words for Andorid viaJava]をインストールします（https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)アプリケーション。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docmument
Docmument docmument = new Docmument("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-ott/" name="PPS に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-dotm/" name="PPS に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-flatopc/" name="PPS に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-dot/" name="PPS に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-rtf/" name="PPS に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-docm/" name="PPS に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-text/" name="PPS に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-docmx/" name="PPS に DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-wordml/" name="PPS に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-word/" name="PPS に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-dotx/" name="PPS に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/pps-to-odt/" name="PPS に ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}