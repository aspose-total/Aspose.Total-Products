---
title: Javaを介してEPUBをWMZに変換する
description: サードパーティのアプリケーションを使用せずに、JavaアプリケーションのWMZにEPUBファイルをエクスポートします
url_ignore: /ja/java/conversion/epub-to-wmz/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: WMZ
otherformats: WMZ DXF  IMAGE JPEG2000 SVGZ PSD WMF EMZ TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してEPUBをWMZに変換する" h2="Adobe <sup>＆reg; </ sup> Acrobat Readerを使用せずに、Java J2SE、J2EE、J2MEアプリケーション内の任意の場所でEPUBファイルをWMZにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単なステップでepubファイルをJavaでWMZ画像に変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用すると、EPUBをJPEGにエクスポートできます。その後、[Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)Image Processing APIを使用して、JPEGをWMZにレンダリングできます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でEPUBをWMZにエクスポート" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してEPUBファイルを開きます
2. JpegDeviceクラスオブジェクトを初期化し、[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)を使用してEPUBをJPEGにレンダリングします。 aspose.pdf.Page-java.io.OutputStream-)メソッド
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してJPEGファイルをロードします
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBaseを使用してドキュメントをWMZ形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://downloads.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介して単一ファイルでEPUBをWMZに変換する" %}}
APIを使用すると、EPUBファイルをWMZの単一ファイルにエクスポートすることもできます。すべてのページを変換するには、最初にEPUBドキュメントを1つのTIFFファイルにレンダリングし、その後、TIFFファイルをWMZにエクスポートできます。 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して入力ファイルを開き、Resolution、TiffSettings、およびTIFFデバイスオブジェクトを作成できます。 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-を使用して単一のTIFF画像を取得できますjava.io.OutputStream-)[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice)クラスのメソッド。最後に、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用してTIFFファイルをロードし、[save](https：// apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-)メソッド。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}/com.aspose.imaging
{{% blocks/products/pf/feature-page-section  h2="Javaを介して透かし付きのEPUBをWMZに変換する" %}}
APIを使用して、WMZドキュメントに透かしを入れたEPUBファイルをWMZにエクスポートすることもできます。透かしを追加するには、最初にEPUBをJPEGに変換し、透かしを追加します。透かしを追加するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して画像ファイルを読み込み、[Graphics](https ：//apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)クラスをImageオブジェクトで初期化し、新しい[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging / Matrix)オブジェクトを作成し、変換と変換を目的の角度に設定し、[Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-)メソッド。画像に透かしを追加した後、JPEGをWMZ形式で保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してEPUBをWMZファイルに変換および回転" %}}
APIを使用すると、必要に応じて出力WMZ画像を回転させることもできます。 Image.rotateFlipメソッドを使用すると、画像を90/180/270度回転し、画像を水平または垂直に反転できます。ライブラリは、すべての醜い詳細をカプセル化しながら、複雑な操作を実行するための簡単なメソッドを提供します。画像に適用する回転と反転のタイプを指定できます。画像を回転および反転するには、[Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)クラスを使用して変換されたJPEG画像をロードし、Imageを呼び出すことができます。適切な[RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)を指定しながらrotateFlipメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

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