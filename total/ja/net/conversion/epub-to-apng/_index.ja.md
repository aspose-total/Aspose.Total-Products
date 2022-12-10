---
title: C＃APIを介してEPUBをAPNGに変換する
description: サードパーティのアプリケーションを使用せずに、.NETアプリケーションでEPUBをAPNGにエクスポートします
url_ignore: /ja/net/conversion/epub-to-apng/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: APNG
otherformats: DXF  PSD SVGZ EMZ JPEG2000 TGA WMZ WMF IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してEPUBファイルをAPNGに変換します" h2="Adobe<sup>＆reg;</sup>AcrobatReaderまたはその他のサードパーティアプリケーションを使用せずに.NETアプリケーション内でEPUBをAPNGにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順で任意の.NETアプリケーション内のAPNGイメージにEPUBを簡単にエクスポートできます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBをJPEGにエクスポートできます。その後、[Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)Image Processing APIを使用して、JPEGをAPNGに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET経由でEPUBファイルをAPNGに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してEPUBファイルを開きます
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)クラスオブジェクトを初期化し、[Process](https：//apireference.aspose)を使用してEPUBをJPEGにレンダリングします。 com / pdf / net / aspose.pdf.devices.pagedevice / process / methods / 1)メソッド
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してJPEGファイルをロードします
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してドキュメントをAPNG形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して単一ファイルでEPUBファイルをAPNGに変換する" %}}
APIを使用して、EPUBファイルをAPNGに変換して単一の画像ファイルにすることもできます。すべてのページを変換するには、最初にEPUBドキュメントを1つのTIFFファイルにレンダリングし、その後TIFFファイルをAPNGにエクスポートできます。 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [TiffDevice](https//apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) の[Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3)メソッドを使用して単一のTIFF画像を取得できますクラス。最後に、[画像](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してTIFFファイルを読み込むことができます
[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してAPNG形式で保存します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介してEPUBファイルをAPNGに変換および回転します" %}}
APIを使用すると、必要に応じて出力APNG画像を回転させることもできます。 Image.RotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスで公開されているファクトリメソッドを使用して変換されたJPEG画像を読み込み、画像を呼び出します。適切な[RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)を指定しながら.RotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-emz/" name="EPUB に EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-tga/" name="EPUB に TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-jpeg2000/" name="EPUB に JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-image/" name="EPUB に IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-psd/" name="EPUB に PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-wmz/" name="EPUB に WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-svgz/" name="EPUB に SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to/" name="EPUB に" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-wmf/" name="EPUB に WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-dxf/" name="EPUB に DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/epub-to-dicom/" name="EPUB に DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}