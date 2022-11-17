---
title: Java経由でAndoridのOTTにPOTMをエクスポートする
description: ソフトウェアをインストールせずにモバイルアプリでPOTMをOTTに変換する

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: OTT
otherformats: ODT DOC DOCM WORD DOTX TEXT DOT WORDML FLATOPC DOTM RTF DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndoridのOTTにPOTMをレンダリングする" h2="Microsoft PowerPointやWordに依存せずに、Androidアプリ内でPOTMをOTTに変換するファイル形式のAPI" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でファイル形式を操作できます。パッケージで提供されているAPIを使用することで、アプリでPowerPointPOTMからWordOTTへの変換プロセスを自動化できます。
あなたは2つのステップであなたの与えられた文書を変換することができます。 Androidアプリケーション用のPowerPointAPIである[Aspose.SlidesforAndorid via Java](https://products.aspose.com/slides/android-java/)を使用して、POTMをHTMLにレンダリングできます。その後、ドキュメント処理API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、HTMLをOTTに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでのPOTMからOTTへのレンダリング" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPOTMファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)を使用してPOTMをHTMLに変換します。ISaveOptions-)メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument)クラスを使用して変換されたHTMLファイルをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int))メソッドを使用してドキュメントをOTT形式で保存し、Ottを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Slides for Android via Java](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/)と[Aspose.Words for Andorid viaJava]をインストールします（https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository)アプリケーション。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Ottument
Ottument ottument = new Ottument("htmlOutput.html");
// save ottument in OTT format
ottument.save("output.ott",SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-odt/" name="POTM に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-ott/" name="POTM に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-ottm/" name="POTM に OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-word/" name="POTM に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-dotx/" name="POTM に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-text/" name="POTM に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-dot/" name="POTM に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-wordml/" name="POTM に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-flatopc/" name="POTM に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-dotm/" name="POTM に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-rtf/" name="POTM に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/potm-to-ottx/" name="POTM に OTTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}