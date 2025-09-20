---
title: Javaを介してHTMLをJPEG2000に変換する
description: サードパーティのアプリケーションを使用せずに、JavaアプリケーションのJPEG2000にHTMLファイルをエクスポートします
url_ignore: /ja/java/conversion/html-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: JPEG2000
otherformats: WMF DXF EMZ  PSD IMAGE SVGZ WMZ JPEG2000 TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してHTMLをJPEG2000に変換する" h2="Adobe <sup>&reg;</sup> Acrobat Readerを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内の任意の場所でHTMLファイルをJPEG2000にエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単なステップでhtmlファイルをJavaでJPEG2000画像に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、HTMLをJPEGにエクスポートできます。その後、[Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)Image Processing APIを使用して、JPEGをJPEG2000にレンダリングできます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でHTMLをJPEG2000にエクスポート" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してHTMLファイルを開きます
2. JpegDeviceクラスオブジェクトを初期化し、[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)を使用してHTMLをJPEGにレンダリングします。 aspose.pdf.Page-java.io.OutputStream-)メソッド
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してJPEGファイルをロードします
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBaseを使用してドキュメントをJPEG2000形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して単一ファイルでHTMLをJPEG2000に変換する" %}}
APIを使用すると、HTMLファイルをJPEG2000の単一ファイルにエクスポートすることもできます。すべてのページを変換するには、最初にHTMLドキュメントを1つのTIFFファイルにレンダリングし、その後、TIFFファイルをJPEG2000にエクスポートできます。 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)を使用して単一のTIFF画像を取得できますjava.io.OutputStream[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)クラスのメソッド。最後に、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してTIFFファイルをロードし、[save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-)メソッド。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して透かし付きのHTMLをJPEG2000に変換する" %}}
APIを使用して、JPEG2000ドキュメントに透かしを入れたHTMLファイルをJPEG2000にエクスポートすることもできます。透かしを追加するには、最初にHTMLをJPEGに変換し、透かしを追加します。透かしを追加するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して画像ファイルを読み込み、[Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)クラスをImageオブジェクトで初期化し、新しい[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging/Matrix)オブジェクトを作成し、変換と変換を目的の角度に設定し、[Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)メソッド。画像に透かしを追加した後、JPEGをJPEG2000形式で保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してHTMLをJPEG2000ファイルに変換および回転" %}}
APIを使用すると、必要に応じて出力JPEG2000画像を回転させることもできます。 Image.rotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。ライブラリは、すべての醜い詳細をカプセル化しながら、複雑な操作を実行するための簡単なメソッドを提供します。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して変換されたJPEG画像をロードし、Imageを呼び出すことができます。適切な[RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)を指定しながらrotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**HTMLをJPEG2000に変換**することは、ウェブコンテンツから**高圧縮で高品質な画像**を生成するために重要です。JPEG2000は視覚的忠実性を保ちながらファイルサイズを大幅に削減し、デジタルライブラリ、研究アーカイブ、ウェブコンテンツ保存に最適です。HTMLページをJPEG2000画像に変換することで、組織は品質を損なうことなく大量の視覚的ウェブコンテンツを効率的に保存、共有、管理できます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用シナリオ" %}}

- **デジタルライブラリ** – コンパクトで高品質な画像形式でウェブリソースを保存および配布します。
- **アーカイブ用ウェブスナップショット** – コンプライアンスと記録目的でウェブサイトの歴史的バージョンを保存します。
- **eラーニングプラットフォーム** – ウェブレッスンやインタラクティブコンテンツを高品質な視覚的参照に変換します。
- **研究出版物** – 学術論文やレポートに正確なウェブベースの視覚的要素を含めます。
- **ウェブコンテンツ保存** – 視覚的に豊かなウェブページの長期アクセシビリティを維持します。
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

- **HTMLからJPEG2000へのパイプライン** – ウェブページを高圧縮画像に自動変換します。
- **自動化された高品質スナップショット生成** – 複数のページに対して一貫した、視覚的に正確な画像を生成します。
- **大量のアーカイブワークフロー** – 大量のウェブコンテンツを効率的に処理して保存または分析します。
- **エンタープライズレベルのデジタル保存** – 大規模なアーカイブおよびパブリッシングシステムにJPEG2000変換を統合します。
  {{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}