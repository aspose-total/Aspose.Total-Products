---
title: .NETを介してJSON形式をIMAGEに変換する
description: サードパーティの依存関係を使用せずに、C＃でJSONをIMAGEに解析します
url_ignore: /ja/net/conversion/json-to-image/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: WMZ TGA PSD IMAGE DICOM SVGZ EMZ JPEG2000 WMF DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してJSON形式をIMAGEに変換する" h2="サードパーティの依存関係を使用せずにJSONをIMAGEに解析するC＃API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でJSONをIMAGEに解析できます。手順。まず、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)を使用して、JSONをJPEGにエクスポートできます。その後、[Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)を使用して、JPEGをIMAGEに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してJSON形式をIMAGEに変換する" %}}
1.新しい[Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)オブジェクトを作成し、ファイルからJSONデータを読み取ります
2. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)メソッドを使用してJSONをJPEGに変換します
3. [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してJPEGドキュメントをロードします
4. [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してドキュメントをIMAGE形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、C＃を介してJSON形式をIMAGEに変換します" %}}
JSONをIMAGEに解析するときに、[JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)を使用してJSONのレイアウトオプションを設定することもできます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2="透かしを使用してJSON形式をIMAGEに解析します" %}}
APIを使用して、IMAGEドキュメントに透かしを入れたJSONをIMAGEに変換することもできます。透かしを追加するには、最初にJSONドキュメントをJPEGにレンダリングし、それに透かしを追加します。操作を示すために、変換されたJPEG画像をロードし、Matrixクラスのオブジェクトを使用して変換を追加し、[Graphics](https://apireference.aspose.com/imaging/)を使用して画像表面に透かしとして文字列を描画できます。 net / aspose.imaging / graphics)class'[DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring)メソッド。透かしを追加した後、JPEGをIMAGE形式で保存できます。以下は、ドキュメントに斜めの透かしを追加する方法を示すコード例です。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-wmz/" name="JSON に WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-dicom/" name="JSON に DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-psd/" name="JSON に PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-jpeg2000/" name="JSON に JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-tga/" name="JSON に TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-emz/" name="JSON に EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-svgz/" name="JSON に SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-wmf/" name="JSON に WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-image/" name="JSON に IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-dxf/" name="JSON に DXF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}