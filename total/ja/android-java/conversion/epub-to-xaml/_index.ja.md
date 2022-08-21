---
title: AndroidでEPUBをXAMLにエクスポートする
description: MicrosoftWordを使用せずにEPUBをXAMLに変換するAndroidAPI
url: /ja/android-java/conversion/epub-to-xaml/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: XAML
otherformats: POTM SWF POT PPSM PPT PPSX OTP PPS POWERPOINT POTX ODP PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaを介してAndroid上でEPUBをXAMLに変換する" h2="Microsoft <sup>＆reg; </ sup>PowerPointまたはAdobe<sup>＆reg; </ sup> Acrobat Readerを使用せずに、Androidアプリケーション内でEPUBをXAMLに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、Androidアプリケーション内にEPUBからXAMLへの変換機能を統合できます。最初のステップでは、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用してEPUBをPPTXにエクスポートできます。その後、[Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)を使用して、PPTXをXAMLに変換できます。どちらのAPIも、[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをXAMLにエクスポートするAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してEPUBファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)メソッドを使用してEPUBをPPTXに変換します
3. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをXAML形式で保存し、`を設定します。 SaveFormatとしてのXaml`
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/)と[Aspose.Slides for Android via Java](https://docs.aspose.com/slides)をインストールしますアプリケーションの/androidjava/install-aspose-slides-for-android-via-java/)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidでパスワードで保護されたEPUBファイルを開く" %}}
EPUBファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)では、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、[ドキュメント]の新しいインスタンスを初期化できます（https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="AndroidアプリケーションでXAMLファイルのサムネイル画像を作成する" %}}
EPUBをXAMLに変換した後、出力ドキュメントのサムネイル画像を作成することもできます。豊富な機能[Aspose.SlidesforAndroid via Java](https://products.aspose.com/slides/android-java/)を使用すると、[プレゼンテーション](プレゼンテーション](プレゼンテーション]のインスタンスを作成してスライドのサムネイル画像を生成できます。 https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラス。その後、IDまたはインデックスを使用して任意のスライドの参照を取得し、指定された縮尺で参照されたスライドのサムネイル画像を取得できます。
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a XAML file
Presentation presentation = new Presentation("output.xaml");
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
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-potm/" name="EPUB に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-swf/" name="EPUB に SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-pot/" name="EPUB に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-ppsm/" name="EPUB に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-ppt/" name="EPUB に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-ppsx/" name="EPUB に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-otp/" name="EPUB に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-pps/" name="EPUB に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-powerpoint/" name="EPUB に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-potx/" name="EPUB に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-xaml/" name="EPUB に XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/epub-to-pptm/" name="EPUB に PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}