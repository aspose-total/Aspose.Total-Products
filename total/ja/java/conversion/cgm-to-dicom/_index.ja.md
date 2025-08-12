---
title: Javaを介してCGMをDICOMに変換する
description: サードパーティのアプリケーションを使用せずに、JavaアプリケーションのDICOMにCGMファイルをエクスポートします
url_ignore: /ja/java/conversion/cgm-to-dicom/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DICOM
otherformats: EMZ PSD WMF WMZ TGA DICOM DXF SVGZ IMAGE JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してCGMをDICOMに変換する" h2="Adobe <sup>&reg;</sup> Acrobat Readerを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内の任意の場所でCGMファイルをDICOMにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単なステップでcgmファイルをJavaでDICOM画像に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、CGMをJPEGにエクスポートできます。その後、[Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)Image Processing APIを使用して、JPEGをDICOMにレンダリングできます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でCGMをDICOMにエクスポート" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してCGMファイルを開きます
2. JpegDeviceクラスオブジェクトを初期化し、[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)を使用してCGMをJPEGにレンダリングします。 aspose.pdf.Page-java.io.OutputStream-)メソッド
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してJPEGファイルをロードします
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBaseを使用してドキュメントをDICOM形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して単一ファイルでCGMをDICOMに変換する" %}}
APIを使用すると、CGMファイルをDICOMの単一ファイルにエクスポートすることもできます。すべてのページを変換するには、最初にCGMドキュメントを1つのTIFFファイルにレンダリングし、その後、TIFFファイルをDICOMにエクスポートできます。 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)を使用して単一のTIFF画像を取得できますjava.io.OutputStream[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)クラスのメソッド。最後に、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してTIFFファイルをロードし、[save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-)メソッド。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して透かし付きのCGMをDICOMに変換する" %}}
APIを使用して、DICOMドキュメントに透かしを入れたCGMファイルをDICOMにエクスポートすることもできます。透かしを追加するには、最初にCGMをJPEGに変換し、透かしを追加します。透かしを追加するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して画像ファイルを読み込み、[Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)クラスをImageオブジェクトで初期化し、新しい[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging/Matrix)オブジェクトを作成し、変換と変換を目的の角度に設定し、[Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)メソッド。画像に透かしを追加した後、JPEGをDICOM形式で保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してCGMをDICOMファイルに変換および回転" %}}
APIを使用すると、必要に応じて出力DICOM画像を回転させることもできます。 Image.rotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。ライブラリは、すべての醜い詳細をカプセル化しながら、複雑な操作を実行するための簡単なメソッドを提供します。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して変換されたJPEG画像をロードし、Imageを呼び出すことができます。適切な[RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)を指定しながらrotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ 主要なユースケース

- **Java 統合型放射線ビューア**  
  診断解釈を向上させるために、CGM ベースの医療図解を Java ベースの DICOM ビューア内で直接表示します。

- **病院情報システム (HIS)**  
  病院ネットワーク全体でアクセス可能な標準化された画像記録のために、CGM を DICOM に変換します。

- **放射線データ交換**  
  DICOM のグローバル標準を使用して、医療施設間で変換された画像ファイルのスムーズな転送を実現します。

- **診断の視覚化**  
  多様な画像形式を統一し、PACS、放射線ビューア、AI による診断ツールでアクセス可能にすることで、臨床ワークフローを改善します。


## ⚙️ 自動化シナリオ

- **DICOM ハンドリングのための Java API**  
  画像処理と DICOM メタデータ管理のための Java ライブラリを使用して、CGM から DICOM への変換パイプラインを自動化します。

- **PACS システム統合**  
  変換された DICOM 画像を直接 Picture Archiving and Communication Systems に供給し、瞬時に取得および保存します。

- **Java ベースの ETL パイプライン**  
  病院全体の画像データ管理のために、自動変換を Extract-Transform-Load ワークフローに統合します。

- **AI による診断ワークフロー**  
  変換された DICOM 画像を分析するために Java 統合 AI モデルを使用し、パターン認識、異常検出、予測診断を行います。
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}