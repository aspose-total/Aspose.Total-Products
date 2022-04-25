---
title: C＃APIを介してPCLをIMAGEに変換する
description: サードパーティのアプリケーションを使用せずに、.NETアプリケーションでPCLをIMAGEにエクスポートします
url: /ja/net/conversion/pcl-to-image/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: JPEG2000
otherformats: EMZ  SVGZ PSD JPEG2000 WMF WMZ IMAGE DXF TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してPCLファイルをIMAGEに変換します" h2="Adobe <sup>＆reg; </ sup>AcrobatReaderまたはその他のサードパーティアプリケーションを使用せずに.NETアプリケーション内でPCLをIMAGEにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/）を使用すると、2つの簡単な手順で任意の.NETアプリケーション内のIMAGEイメージにPCLを簡単にエクスポートできます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/）を使用すると、PCLをJPEGにエクスポートできます。その後、[Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/）Image Processing APIを使用して、JPEGをIMAGEに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET経由でPCLファイルをIMAGEに変換する" %}}
1. [ドキュメント](https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスを使用してPCLファイルを開きます
2. [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice）クラスオブジェクトを初期化し、[Process](https：//apireference.aspose）を使用してPCLをJPEGにレンダリングします。 com / pdf / net / aspose.pdf.devices.pagedevice / process / methods / 1）メソッド
3. [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image）クラスを使用してJPEGファイルをロードします
4. [保存](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4）メソッドを使用してドキュメントをIMAGE形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して単一ファイルでPCLファイルをIMAGEに変換する" %}}](https:](https:](https:
API](https:LファイルをIMAGEに変換して単一の画像ファイルにすることもできます。すべてのページを変換するには、最初にPCLドキュメントを1つのTIFFファイルにレンダリングし、その後TIFFファイルをIMAGEにエクスポートできます。 [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [TiffDevice](https：//の[Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3）メソッドを使用して単一のTIFF画像を取得できますapireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice）クラス。最後に、[画像](https://apireference.aspose.com/imaging/net/aspose.imaging/image）クラスを使用してTIFFファイルを読み込むことができます
[保存](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4）メソッドを使用してIMAGE形式で保存します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https:](https:
{{% blocks/products/pf/feature-page-section  h2="C＃を介してPCLファイルをIMAGEに変換および回転します" %}}
APIを使用すると、必要に応じて出力IMAGE画像を回転させることもできます。 Image.RotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image）クラスで公開されているファクトリメソッドを使用して変換されたJPEG画像を読み込み、画像を呼び出します。適切な[RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype）を指定しながら.RotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-emz/" name="PCL に EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-tga/" name="PCL に TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-jpeg2000/" name="PCL に JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-image/" name="PCL に IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-psd/" name="PCL に PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-wmz/" name="PCL に WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-svgz/" name="PCL に SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to/" name="PCL に" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-wmf/" name="PCL に WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-dxf/" name="PCL に DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pcl-to-dicom/" name="PCL に DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}