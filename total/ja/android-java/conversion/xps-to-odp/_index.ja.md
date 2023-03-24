---
title: AndroidでXPSをODPにエクスポートする
description: MicrosoftWordを使用せずにXPSをODPに変換するAndroidAPI

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: ODP
otherformats: PPSM PPSX PPTM POTM POT XAML SWF PPT OTP POTX POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaを介してAndroid上でXPSをODPに変換する" h2="Microsoft <sup>＆reg; </ sup>PowerPointまたはAdobe<sup>＆reg; </ sup> Acrobat Readerを使用せずに、Androidアプリケーション内でXPSをODPに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、Androidアプリケーション内にXPSからODPへの変換機能を統合できます。最初のステップでは、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用してXPSをPPTXにエクスポートできます。その後、[Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)を使用して、PPTXをODPに変換できます。どちらのAPIも、[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPSをODPにエクスポートするAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してXPSファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)メソッドを使用してXPSをPPTXに変換します
3. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをODP形式で保存し、`を設定します。 SaveFormatとしてのOdp`
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/)と[Aspose.Slides for Android via Java](https://docs.aspose.com/slides)をインストールしますアプリケーションの/androidjava/install-aspose-slides-for-android-via-java/)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidでパスワードで保護されたXPSファイルを開く" %}}
XPSファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)では、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、[ドキュメント]の新しいインスタンスを初期化できます（https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="AndroidアプリケーションでODPファイルのサムネイル画像を作成する" %}}
XPSをODPに変換した後、出力ドキュメントのサムネイル画像を作成することもできます。豊富な機能[Aspose.SlidesforAndroid via Java](https://products.aspose.com/slides/android-java/)を使用すると、[プレゼンテーション](プレゼンテーション](プレゼンテーション]のインスタンスを作成してスライドのサムネイル画像を生成できます。 https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラス。その後、IDまたはインデックスを使用して任意のスライドの参照を取得し、指定された縮尺で参照されたスライドのサムネイル画像を取得できます。
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("output.odp");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}