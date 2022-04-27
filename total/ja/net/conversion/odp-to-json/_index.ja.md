---
title: .NETを介してODPをJSON形式に変換する
description: Microsoft ExcelまたはPowerpointを使用せずにC＃でODPをJSONに変換する
url: /ja/net/conversion/odp-to-json/
family: total
platformtag: net
feature: conversion
informat: ODP
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してODPをJSON形式に変換する" h2="Microsoft<sup>＆reg;</sup> ExcelまたはPowerPointを使用せずにC＃経由でODPをJSONにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET]（https://products.aspose.com/total/net/）を使用すると、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でODPをJSON形式に変換できます。簡単な手順。まず、[Aspose.Slides for .NET]（https://products.aspose.com/slides/net/）を使用すると、ODPをHTMLにエクスポートできます。その後、[Aspose.Cells for .NET]（https://products.aspose.com/cells/net/）Spreadsheet Programming APIを使用して、HTMLをJSONに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してODPをJSON形式に変換する" %}}
1. [プレゼンテーション]（https://apireference.aspose.com/slides/net/aspose.slides/presentation）クラスを使用してODPファイルを開きます
2. [保存]（https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5）メソッドを使用してODPをHTMLに変換します
3. [ワークブック]（https://apireference.aspose.com/cells/net/aspose.cells/workbook）クラスを使用してHTMLドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4）メソッドを使用してドキュメントをJSON形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード]（https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたODPをC＃経由でJSON形式に変換する" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力ODPドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。 APIを使用すると、LoadOptionsオブジェクトで正しいパスワードを渡すことにより、暗号化されたドキュメントを開くことができます。次のコード例は、パスワードを使用して暗号化されたドキュメントを開く方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介してODPを範囲内のJSONに変換する" %}}
ODPをJSONに変換しているときに、範囲を出力JSON形式に設定することもできます。範囲を設定するには、Workbookクラスを使用して変換されたHTMLを開き、データを含むワークシートのCellsCollectionを取得し、行と列のインデックスを指定してCellsCollectionから範囲を作成し、RangeオブジェクトとExportRangeToJsonOptionsオブジェクトを参照してExportRangeToJsonメソッドを呼び出します。最後に、File.WriteAllTextメソッドを使用してJSONデータをファイルに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-doc/" name="ODP に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-docm/" name="ODP に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-docx/" name="ODP に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-dot/" name="ODP に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-dotm/" name="ODP に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-dotx/" name="ODP に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-odt/" name="ODP に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-ott/" name="ODP に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-rtf/" name="ODP に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-text/" name="ODP に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-word/" name="ODP に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/odp-to-wordml/" name="ODP に WORDML" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}