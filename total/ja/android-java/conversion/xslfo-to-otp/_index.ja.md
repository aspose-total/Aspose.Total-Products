---
title: AndroidでXSLFOをOTPにエクスポートする
description: MicrosoftWordを使用せずにXSLFOをOTPに変換するAndroidAPI

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: OTP
otherformats: PPT PPSM POWERPOINT POT PPSX POTX POTM XAML PPTM ODP SWF PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaを介してAndroid上でXSLFOをOTPに変換する" h2="Microsoft <sup>＆reg; </ sup>PowerPointまたはAdobe<sup>＆reg; </ sup> Acrobat Readerを使用せずに、Androidアプリケーション内でXSLFOをOTPに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、Androidアプリケーション内にXSLFOからOTPへの変換機能を統合できます。最初のステップでは、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用してXSLFOをPPTXにエクスポートできます。その後、[Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)を使用して、PPTXをOTPに変換できます。どちらのAPIも、[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFOをOTPにエクスポートするAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してXSLFOファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)メソッドを使用してXSLFOをPPTXに変換します
3. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをOTP形式で保存し、`を設定します。 SaveFormatとしてのOtp`
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/)と[Aspose.Slides for Android via Java](https://docs.aspose.com/slides)をインストールしますアプリケーションの/androidjava/install-aspose-slides-for-android-via-java/)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidでパスワードで保護されたXSLFOファイルを開く" %}}
XSLFOファイル形式の読み込み中、ドキュメントはパスワードで保護されている可能性があります。 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)では、暗号化されたドキュメントを開くこともできます。暗号化されたファイルを開くために、[ドキュメント]の新しいインスタンスを初期化できます（https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="AndroidアプリケーションでOTPファイルのサムネイル画像を作成する" %}}
XSLFOをOTPに変換した後、出力ドキュメントのサムネイル画像を作成することもできます。豊富な機能[Aspose.SlidesforAndroid via Java](https://products.aspose.com/slides/android-java/)を使用すると、[プレゼンテーション](プレゼンテーション](プレゼンテーション]のインスタンスを作成してスライドのサムネイル画像を生成できます。 https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラス。その後、IDまたはインデックスを使用して任意のスライドの参照を取得し、指定された縮尺で参照されたスライドのサムネイル画像を取得できます。
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("output.otp");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-ppt/" name="XSLFO に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-ppsm/" name="XSLFO に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-powerpoint/" name="XSLFO に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-pot/" name="XSLFO に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-ppsx/" name="XSLFO に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-potx/" name="XSLFO に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-potm/" name="XSLFO に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-xaml/" name="XSLFO に XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-pptm/" name="XSLFO に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-otp/" name="XSLFO に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-swf/" name="XSLFO に SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xslfo-to-pps/" name="XSLFO に PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}