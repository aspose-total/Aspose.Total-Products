---
title: .NETを介してJSON形式をPSDに変換する
description: サードパーティの依存関係を使用せずに、C＃でJSONをPSDに解析します
url_ignore: /ja/net/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: EMZ WMZ PSD WMF JPEG2000 DXF DICOM IMAGE SVGZ TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してJSON形式をPSDに変換する" h2="サードパーティの依存関係を使用せずにJSONをPSDに解析するC＃API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でJSONをPSDに解析できます。手順。まず、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)を使用して、JSONをJPEGにエクスポートできます。その後、[Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)を使用して、JPEGをPSDに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してJSON形式をPSDに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)オブジェクトを作成し、ファイルからJSONデータを読み取ります
2. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)メソッドを使用してJSONをJPEGに変換します
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)クラスを使用してJPEGドキュメントをロードします
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)メソッドを使用してドキュメントをPSD形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、C＃を介してJSON形式をPSDに変換します" %}}
JSONをPSDに解析するときに、[JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)を使用してJSONのレイアウトオプションを設定することもできます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2="透かしを使用してJSON形式をPSDに解析します" %}}
APIを使用して、PSDドキュメントに透かしを入れたJSONをPSDに変換することもできます。透かしを追加するには、最初にJSONドキュメントをJPEGにレンダリングし、それに透かしを追加します。操作を示すために、変換されたJPEG画像をロードし、Matrixクラスのオブジェクトを使用して変換を追加し、[Graphics](https://reference.aspose.com/imaging/)を使用して画像表面に透かしとして文字列を描画できます。 net / aspose.imaging / graphics)class'[DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring)メソッド。透かしを追加した後、JPEGをPSD形式で保存できます。以下は、ドキュメントに斜めの透かしを追加する方法を示すコード例です。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}