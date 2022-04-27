---
title: .NETを介してDOTXをJSON形式に変換します
description: MicrosoftExcelまたはAdobeReaderを使用せずにC＃でDOTXをJSONに変換する
url: /ja/net/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: XLT EXCEL ODS XLTM TSV XLAM SXC DIF XLS XLSB XLTX XLSX CSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してDOTXをJSON形式に変換する" h2="Microsoft<sup>＆reg;</sup> WordまたはExcelを使用せずに、C＃を介してDOTXをJSONに解析します" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET]（https://products.aspose.com/total/net/）を使用すると、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でDOTXをJSON形式に変換できます。簡単な手順。まず、[Aspose.Words for .NET]（https://products.aspose.com/words/net/）を使用して、DOTXをHTMLにエクスポートできます。その後、[Aspose.Cells for .NET]（https://products.aspose.com/cells/net/）Spreadsheet Programming APIを使用して、HTMLをJSONに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してDOTXをJSON形式に変換する" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/net/aspose.words/dotxument）クラスを使用してDOTXファイルを開きます
2. [保存]（https://apireference.aspose.com/words/net/aspose.words.dotxument/save/methods/4）メソッドを使用してDOTXをHTMLに変換します
3. [ワークブック]（https://apireference.aspose.com/cells/net/aspose.cells/workbook）クラスを使用してHTMLドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4）メソッドを使用してドキュメントをJSON形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード]（https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたDOTXをC＃経由でJSON形式に変換する" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力DOTXドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。 APIを使用すると、LoadOptionsオブジェクトで正しいパスワードを渡すことにより、暗号化されたドキュメントを開くことができます。次のコード例は、パスワードを使用して暗号化されたドキュメントを開こうとする方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して範囲内のDOTXをJSONに変換する" %}}
DOTXをJSONに変換しているときに、範囲を出力JSON形式に設定することもできます。範囲を設定するには、Workbookクラスを使用して変換されたHTMLを開き、データを含むワークシートのCellsCollectionを取得し、行と列のインデックスを指定してCellsCollectionから範囲を作成し、RangeオブジェクトとExportRangeToJsonOptionsオブジェクトを参照してExportRangeToJsonメソッドを呼び出します。最後に、File.WriteAllTextメソッドを使用してJSONデータをファイルに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-csv/" name="DOTX に CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xlam/" name="DOTX に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-sxc/" name="DOTX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-tsv/" name="DOTX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xlt/" name="DOTX に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-excel/" name="DOTX に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-dif/" name="DOTX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xlsm/" name="DOTX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xltm/" name="DOTX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xlsx/" name="DOTX に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xlsb/" name="DOTX に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-fods/" name="DOTX に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-ods/" name="DOTX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dotx-to-xltx/" name="DOTX に XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}