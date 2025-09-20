---
title: Javaを介してHTMLをIMAGEに変換する
description: サードパーティのアプリケーションを使用せずに、JavaアプリケーションのIMAGEにHTMLファイルをエクスポートします
url_ignore: /ja/java/conversion/html-to-image/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: JPEG2000
otherformats: EMZ JPEG2000 PSD WMF TGA SVGZ WMZ DXF IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してHTMLをIMAGEに変換する" h2="Adobe <sup>&reg;</sup> Acrobat Readerを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内の任意の場所でHTMLファイルをIMAGEにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単なステップでhtmlファイルをJavaでIMAGE画像に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、HTMLをJPEGにエクスポートできます。その後、[Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)Image Processing APIを使用して、JPEGをIMAGEにレンダリングできます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でHTMLをIMAGEにエクスポート" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してHTMLファイルを開きます
2. JpegDeviceクラスオブジェクトを初期化し、[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)を使用してHTMLをJPEGにレンダリングします。 aspose.pdf.Page-java.io.OutputStream-)メソッド
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してJPEGファイルをロードします
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)を使用してドキュメントをIMAGE形式で保存します- 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して単一ファイルでHTMLをIMAGEに変換する" %}}
APIを使用すると、HTMLファイルをIMAGEの単一ファイルにエクスポートすることもできます。すべてのページを変換するには、最初にHTMLドキュメントを1つのTIFFファイルにレンダリングし、その後、TIFFファイルをIMAGEにエクスポートできます。 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)を使用して単一のTIFF画像を取得できますjava.io.OutputStream[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)クラスのメソッド。最後に、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してTIFFファイルをロードし、[save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-)メソッド。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して透かし付きのHTMLをIMAGEに変換する" %}}
APIを使用して、IMAGEドキュメントに透かしを入れたHTMLファイルをIMAGEにエクスポートすることもできます。透かしを追加するには、最初にHTMLをJPEGに変換し、透かしを追加します。透かしを追加するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して画像ファイルを読み込み、[Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)クラスをImageオブジェクトで初期化し、新しい[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging/Matrix)オブジェクトを作成し、変換と変換を目的の角度に設定し、[Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)メソッド。画像に透かしを追加した後、JPEGをIMAGE形式で保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してHTMLをIMAGEファイルに変換および回転" %}}
APIを使用すると、必要に応じて出力IMAGE画像を回転させることもできます。 Image.rotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。ライブラリは、すべての醜い詳細をカプセル化しながら、複雑な操作を実行するための簡単なメソッドを提供します。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して変換されたJPEG画像をロードし、Imageを呼び出すことができます。適切な[RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)を指定しながらrotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**HTML**を**IMAGE**に変換することは、Webページの正確なビジュアルスナップショットをキャプチャするために不可欠です。このプロセスにより、デザイナーやマーケター、開発者が、動的または静的なWebコンテンツを共有可能で閲覧可能な画像に変換し、デバイス間でウェブサイトの外観や雰囲気を維持することができます。Webページの画像表現を作成することで、チームはプレビューを効率化し、デジタルコンテンツを強化し、視覚的な記録を効率的に維持することができます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用事例" %}}

* **ウェブサイトのプレビュー:** ポートフォリオ、クライアントレビュー、またはクイックビジュアルリファレンス用のスナップショットを生成します。
* **インフォグラフィック:** データ豊富なWebページを共有可能なビジュアル形式に変換します。
* **UI/UXデザインワークフロー:** テスト、フィードバック、および反復のためのページデザインをキャプチャします。
* **アーカイブスクリーンショット:** コンプライアンスまたは文書化のためにウェブサイトの歴史的なバージョンを保存します。
* **デジタルマーケティング資産:** ウェブコンテンツから直接、バナー、ソーシャルメディアのビジュアル、プロモーショングラフィックスを作成します。
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **HTML-to-IMAGEパイプライン:** 手動作業を最小限に抑えて複数のWebページを画像にシームレスに変換します。
* **自動化されたWebページから画像へのレンダリング:** レポート作成や監視のために動的ページのレンダリングをスケジュールします。
* **大量スクリーンショット生成:** 大規模プロジェクト向けに同時に数百ページをキャプチャします。
* **エンタープライズ規模のデジタルパブリッシング:** ウェブサイト、ニュースレター、または製品カタログ向けのコンテンツワークフローに画像生成を統合します。
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}