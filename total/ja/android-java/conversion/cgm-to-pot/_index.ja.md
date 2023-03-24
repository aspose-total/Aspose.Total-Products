---
title: AndroidでCGMをPOTにエクスポートする
description: MicrosoftWordを使用せずにCGMをPOTに変換するAndroidAPI

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: POT
otherformats: PPTM PPT XAML PPS ODP SWF OTP POTM POWERPOINT POTX PPSM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaを介してAndroid上でCGMをPOTに変換する" h2="Microsoft <sup>＆reg; </ sup>PowerPointまたはAdobe<sup>＆reg; </ sup> Acrobat Readerを使用せずに、Androidアプリケーション内でCGMをPOTに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、Androidアプリケーション内にCGMからPOTへの変換機能を統合できます。最初のステップでは、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用してCGMをPPTXにエクスポートできます。その後、[Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)を使用して、PPTXをPOTに変換できます。どちらのAPIも、[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをPOTにエクスポートするAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してCGMファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)メソッドを使用してCGMをPPTXに変換します
3. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをPOT形式で保存し、`を設定します。 SaveFormatとしてのPot`
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/)と[Aspose.Slides for Android via Java](https://docs.aspose.com/slides)をインストールしますアプリケーションの/androidjava/install-aspose-slides-for-android-via-java/)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidでパスワードで保護されたCGMファイルを開く" %}}
CGMファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)では、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、[ドキュメント]の新しいインスタンスを初期化できます（https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="AndroidアプリケーションでPOTファイルのサムネイル画像を作成する" %}}
CGMをPOTに変換した後、出力ドキュメントのサムネイル画像を作成することもできます。豊富な機能[Aspose.SlidesforAndroid via Java](https://products.aspose.com/slides/android-java/)を使用すると、[プレゼンテーション](プレゼンテーション](プレゼンテーション]のインスタンスを作成してスライドのサムネイル画像を生成できます。 https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラス。その後、IDまたはインデックスを使用して任意のスライドの参照を取得し、指定された縮尺で参照されたスライドのサムネイル画像を取得できます。
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
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