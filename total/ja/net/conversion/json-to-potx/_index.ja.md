---
title: .NETを介してJSON形式をPOTXに変換する
description: Microsoft PowerPointを使用せずにC＃でJSONをPOTXに解析する
url_ignore: /ja/net/conversion/json-to-potx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX OTP POTM PPS POWERPOINT PPTM POTX PPT POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してJSON形式をPOTXに変換する" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにJSONをPOTXに解析するC＃API" >}}

{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順で、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でJSONをPOTXに変換できます。まず、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)を使用して、JSONをPPTXに解析できます。その後、[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをPOTXに変換できます。どちらのAPIも、[Aspose.Total for .NET](https://products.aspose.com/total/net/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してJSON形式をPOTXに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility)クラスと[Save](https://reference.aspose.com/)を使用して、JSONファイルをワークシートにインポートします。 cells / net / aspose.cells.workbook / save / methods / 4)PPTXとして
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXドキュメントをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをPOTX形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、C＃を介してJSON形式をPOTXに変換します" %}}
JSONをPOTXに解析するときに、[JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)を使用してJSON形式のレイアウトオプションを設定することもできます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="透かしを使用してJSON形式をPOTXに変換する" %}}
APIを使用して、JSONを透かし付きのPOTXに変換することもできます。 POTXドキュメントに透かしを追加するには、最初にJSONをPPTXに解析し、それに透かしを追加します。透かしを追加するには、[Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用して新しく作成されたPPTXファイルをロードし、マスタープレゼンテーションを選択し、を使用して形状タイプを追加します。 AddAutoShapeを作成し、AddTextFrameを使用して透かしテキストを追加します。透かしを追加した後、ドキュメントをPOTXに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}