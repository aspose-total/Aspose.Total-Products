---
title: C＃APIを介してCGMをJPEG2000に変換する
description: サードパーティのアプリケーションを使用せずに、.NETアプリケーションでCGMをJPEG2000にエクスポートします
url_ignore: /ja/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してCGMファイルをJPEG2000に変換します" h2="Adobe<sup>＆reg;</sup>AcrobatReaderまたはその他のサードパーティアプリケーションを使用せずに.NETアプリケーション内でCGMをJPEG2000にエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順で任意の.NETアプリケーション内のJPEG2000イメージにCGMを簡単にエクスポートできます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMをJPEGにエクスポートできます。その後、[Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)Image Processing APIを使用して、JPEGをJPEG2000に変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET経由でCGMファイルをJPEG2000に変換する" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)クラスオブジェクトを初期化し、[Process](https：//apireference.aspose)を使用してCGMをJPEGにレンダリングします。 com / pdf / net / aspose.pdf.devices.pagedevice / process / methods / 1)メソッド
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してJPEGファイルをロードします
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してドキュメントをJPEG2000形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して単一ファイルでCGMファイルをJPEG2000に変換する" %}}
APIを使用して、CGMファイルをJPEG2000に変換して単一の画像ファイルにすることもできます。すべてのページを変換するには、最初にCGMドキュメントを1つのTIFFファイルにレンダリングし、その後TIFFファイルをJPEG2000にエクスポートできます。 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [TiffDevice](https//apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) の[Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3)メソッドを使用して単一のTIFF画像を取得できますクラス。最後に、[画像](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してTIFFファイルを読み込むことができます
[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してJPEG2000形式で保存します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介してCGMファイルをJPEG2000に変換および回転します" %}}
APIを使用すると、必要に応じて出力JPEG2000画像を回転させることもできます。 Image.RotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスで公開されているファクトリメソッドを使用して変換されたJPEG画像を読み込み、画像を呼び出します。適切な[RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)を指定しながら.RotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをJPEG2000に変換する：ユースケース" %}}
CGM（コンピュータグラフィックスメタファイル）形式のファイルは、ベクターグラフィックス情報を保存するために使用されます。静的なグラフィックやイラストレーションを作成する際には、理想的です。しかし、ダイナミックなデータと仕事をする場合には、JPEG 2000 形式の画像が最適な圧縮と品質を実現するために必要です。

CGM ファイルを JPEG 2000 形式に変換することは、イメージの圧缩と品質の限界を引き出すためになります。この変換により、次のような用途で役立ちます：

**用途:**

* **高品質なイメージエディット**: CGM ファイルをJPEG 2000 形式に変換し、高品質な画像を作成し、ウェブでの利用向上や全社的なブランド統一を確保することができます。
* **アーカイヴと保存応用**: 大量のイメージ データを JPEG 2000 で 圧縮し、長期的な保存とアクセシビリティーを確保するために使用します。
* **医療画像と診断**: CGM ファイルをJPEG 2000 形式に変換し、高品質な医療画像を作成し、診断の精度を向上し、患者への利益を 增加させることができます。
* **科学研究と出版**: 科学的なイメージ データを JPEG 2000 で 圧縮し、グローバルな協力と知識共有を促進するために使用します。
* **デジタル ライブラリとアーカイヴ**: CGM ファイルをJPEG 2000 形式に変換し、スケーラブルな、高品質なデジタル ライブラリを作成し、文化的遺産や歴史的な資料を未来世代まで保存します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}