---
title: .NETを介してJSON形式をCHMに変換する
description: Microsoft Wordを使用せずにC＃でJSONをCHMに解析する
url_ignore: /ja/net/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: OTT FLATOPC PS DOTX RTF WORDML ODT WORD EPUB DOC DOT PCL MOBI DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してJSON形式をCHMに変換する" h2="Microsoft<sup>＆reg;</sup>Wordを使用せずにJSONをCHMに解析するC＃API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内のJSONからCHMを2つの簡単な方法で解析できます。手順。まず、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)を使用して、JSONをPDFにエクスポートできます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、PDFをCHMに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してJSON形式をCHMに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility)クラスと[Save](https://reference.aspose.com/)を使用して、JSONファイルをワークシートにインポートします。 cells / net / aspose.cells.workbook / save / methods / 4)それをPDFとして
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してPDFドキュメントをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)メソッドを使用してドキュメントをCHM形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、C＃を介してJSON形式をCHMに変換します" %}}
JSONをCHMに解析するときに、[JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions)を使用してJSONのレイアウトオプションを設定することもできます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="透かしを使用してJSON形式をCHMに解析します" %}}
APIを使用して、JSONを透かし付きのCHMに変換することもできます。 CHMドキュメントに透かしを追加するには、最初にJSONファイルをPDFに解析し、それに透かしを追加します。透かしを追加するには、[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用して新しく作成したPDFファイルをロードし、TextWatermarkOptionsのインスタンスを作成して、そのプロパティを設定します。 、Watermark.SetTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。透かしを追加した後、ドキュメントをCHMに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}