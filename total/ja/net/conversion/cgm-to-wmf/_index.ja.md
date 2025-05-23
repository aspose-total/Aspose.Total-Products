---
title: C＃APIを介してCGMをWMFに変換する
description: サードパーティのアプリケーションを使用せずに、.NETアプリケーションでCGMをWMFにエクスポートします
url_ignore: /ja/net/conversion/cgm-to-wmf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: WMF
otherformats: EMZ SVGZ WMF TGA JPEG2000 DXF  PSD WMZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してCGMファイルをWMFに変換します" h2="Adobe<sup>＆reg;</sup>AcrobatReaderまたはその他のサードパーティアプリケーションを使用せずに.NETアプリケーション内でCGMをWMFにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順で任意の.NETアプリケーション内のWMFイメージにCGMを簡単にエクスポートできます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMをJPEGにエクスポートできます。その後、[Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)Image Processing APIを使用して、JPEGをWMFに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET経由でCGMファイルをWMFに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)クラスオブジェクトを初期化し、[Process](https：//apireference.aspose)を使用してCGMをJPEGにレンダリングします。 com / pdf / net / aspose.pdf.devices.pagedevice / process / methods / 1)メソッド
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してJPEGファイルをロードします
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してドキュメントをWMF形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して単一ファイルでCGMファイルをWMFに変換する" %}}
APIを使用して、CGMファイルをWMFに変換して単一の画像ファイルにすることもできます。すべてのページを変換するには、最初にCGMドキュメントを1つのTIFFファイルにレンダリングし、その後TIFFファイルをWMFにエクスポートできます。 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [TiffDevice](https//apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) の[Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3)メソッドを使用して単一のTIFF画像を取得できますクラス。最後に、[画像](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してTIFFファイルを読み込むことができます
[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してWMF形式で保存します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介してCGMファイルをWMFに変換および回転します" %}}
APIを使用すると、必要に応じて出力WMF画像を回転させることもできます。 Image.RotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスで公開されているファクトリメソッドを使用して変換されたJPEG画像を読み込み、画像を呼び出します。適切な[RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)を指定しながら.RotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをWMFに変換する：ユースケース" %}}
CGMファイルをWMF形式に変換する必要があります。これにより、グラフィックデザインやビジュアル化表示の最大の潜力を引き出すことができます。以下に、変換後のWMF形式の利用例を示します。

**利用例:**

* **グラフィックデザインとイラストレーション:**  
  CGMファイルをWMF形式で複雑なグラフィックスやイラストレーション、ロゴを作成することができます。これにより、さまざまなメディアでの利用が可能になります。

* **建築視覚化:**  
  WMF形式を用いて、3Dモデル、建物設計、建築計画のビジュアル化表示を行うことができるようになります。このため、クライアントや利害関係者との共同作成と通信が向上します。

* **技術図とCAD:**  
  CGMファイルをWMF形式で技術図、blueprint、CAD設計を作成することができます。これにより、製品開発、製造、工程分野での活用が可能になります。

* **芸術的表現:**  
  WMF形式を用いて、複雑な芸術的表現、グラフィックス、アイコン、ロゴを作成することができるようになります。これにより、創意と技巧を詰め込むことができます。

* **デジタルサイネージとディスプレイ:**  
  CGMファイルをWMF形式でデジタルサイネージ、ディスプレイ、プレゼンテーションを作成することができるようになります。これにより、観客へのエンゲージメントやメッセージの伝達が効率的に行われます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}