---
title: Javaを介してXSLFOをWMZに変換する
description: サードパーティのアプリケーションを使用せずに、JavaアプリケーションのWMZにXSLFOファイルをエクスポートします
url_ignore: /ja/java/conversion/xslfo-to-wmz/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: WMZ
otherformats: PSD  WMZ JPEG2000 SVGZ WMF EMZ IMAGE DXF TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してXSLFOをWMZに変換する" h2="Adobe <sup>&reg;</sup> Acrobat Readerを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内の任意の場所でXSLFOファイルをWMZにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単なステップでxslfoファイルをJavaでWMZ画像に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、XSLFOをJPEGにエクスポートできます。その後、[Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)Image Processing APIを使用して、JPEGをWMZにレンダリングできます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でXSLFOをWMZにエクスポート" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してXSLFOファイルを開きます
2. JpegDeviceクラスオブジェクトを初期化し、[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)を使用してXSLFOをJPEGにレンダリングします。 aspose.pdf.Page-java.io.OutputStream-)メソッド
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してJPEGファイルをロードします
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBaseを使用してドキュメントをWMZ形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して単一ファイルでXSLFOをWMZに変換する" %}}
APIを使用すると、XSLFOファイルをWMZの単一ファイルにエクスポートすることもできます。すべてのページを変換するには、最初にXSLFOドキュメントを1つのTIFFファイルにレンダリングし、その後、TIFFファイルをWMZにエクスポートできます。 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)を使用して単一のTIFF画像を取得できますjava.io.OutputStream[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)クラスのメソッド。最後に、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してTIFFファイルをロードし、[save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-)メソッド。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して透かし付きのXSLFOをWMZに変換する" %}}
APIを使用して、WMZドキュメントに透かしを入れたXSLFOファイルをWMZにエクスポートすることもできます。透かしを追加するには、最初にXSLFOをJPEGに変換し、透かしを追加します。透かしを追加するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して画像ファイルを読み込み、[Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)クラスをImageオブジェクトで初期化し、新しい[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging/Matrix)オブジェクトを作成し、変換と変換を目的の角度に設定し、[Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)メソッド。画像に透かしを追加した後、JPEGをWMZ形式で保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してXSLFOをWMZファイルに変換および回転" %}}
APIを使用すると、必要に応じて出力WMZ画像を回転させることもできます。 Image.rotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。ライブラリは、すべての醜い詳細をカプセル化しながら、複雑な操作を実行するための簡単なメソッドを提供します。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して変換されたJPEG画像をロードし、Imageを呼び出すことができます。適切な[RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)を指定しながらrotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



XSLFOを**WMZ（圧縮Windowsメタファイル）**に変換すると、スケーラビリティを維持しながら、Eメール、プレゼンテーション、Web統合に最適な圧縮されたベクター画像が提供されます。



{{% blocks/products/pf/agp/feature-section-col title="主な使用ケース" %}}



* XSLFOで生成されたビジュアルを圧縮添付ファイルとして送信する。

* PowerPointやWordにスケーラブルなグラフィックを埋め込む。

* 圧縮されたベクターレポートのビジュアルをアーカイブする。

* Eメールや内部ポータルを介して運用ダッシュボードを共有する。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}



* XSLFOファイルをWMZにバッチ変換してスペース効率の良いストレージにする。

* ビジュアルレポートの定期的な自動圧縮をスケジュールする。

* 定期的なプレゼンテーションワークフローのためのトリガー付きWMZ生成。

* 自動化されたスライドデッキやドキュメントパイプラインへの統合。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}