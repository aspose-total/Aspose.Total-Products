---
title: .NETを介してDOCXをJSON形式に変換します
description: MicrosoftExcelまたはAdobeReaderを使用せずにC＃でDOCXをJSONに変換する
url: /ja/net/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C＃を介してDOCXをJSON形式に変換する" h2="Microsoft <sup>＆reg; </ sup> WordまたはExcelを使用せずに、C＃を介してDOCXをJSONに解析します" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET]（https://products.aspose.com/total/net/）を使用すると、任意の.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でDOCXをJSON形式に変換できます。簡単な手順。まず、[Aspose.Words for .NET]（https://products.aspose.com/words/net/）を使用して、DOCXをHTMLにエクスポートできます。その後、[Aspose.Cells for .NET]（https://products.aspose.com/cells/net/）Spreadsheet Programming APIを使用して、HTMLをJSONに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C＃を介してDOCXをJSON形式に変換する" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/net/aspose.words/document）クラスを使用してDOCXファイルを開きます
2. [保存]（https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4）メソッドを使用してDOCXをHTMLに変換します
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

{{% blocks/products/pf/feature-page-section  h2="保護されたDOCXをC＃経由でJSON形式に変換する" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力DOCXドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。 APIを使用すると、LoadOptionsオブジェクトで正しいパスワードを渡すことにより、暗号化されたドキュメントを開くことができます。次のコード例は、パスワードを使用して暗号化されたドキュメントを開こうとする方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して範囲内のDOCXをJSONに変換する" %}}
DOCXをJSONに変換しているときに、範囲を出力JSON形式に設定することもできます。範囲を設定するには、Workbookクラスを使用して変換されたHTMLを開き、データを含むワークシートのCellsCollectionを取得し、行と列のインデックスを指定してCellsCollectionから範囲を作成し、RangeオブジェクトとExportRangeToJsonOptionsオブジェクトを参照してExportRangeToJsonメソッドを呼び出します。最後に、File.WriteAllTextメソッドを使用してJSONデータをファイルに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-csv/" name="DOCX に CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlam/" name="DOCX に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-sxc/" name="DOCX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-tsv/" name="DOCX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlt/" name="DOCX に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-excel/" name="DOCX に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-dif/" name="DOCX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlsm/" name="DOCX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xltm/" name="DOCX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlsx/" name="DOCX に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xlsb/" name="DOCX に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-fods/" name="DOCX に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-ods/" name="DOCX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docx-to-xltx/" name="DOCX に XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}