---
title: C＃APIを介してTEXをXLTに変換する
description: MicrosoftExcelまたはAdobeReaderを使用せずにTEXファイルをXLTに変換するC＃API
url: /ja/net/conversion/tex-to-xlt/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: XLT
otherformats: MD SXC XLTX XLTM XLSM XLAM EXCEL ODS TXT DIF TSV XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TEXをXLTにレンダリングするC＃API" h2="Microsoft<sup>＆reg;</sup>ExcelまたはAdobe<sup>＆reg;</sup> Acrobat Readerを使用せずにC＃経由でTEXファイルをXLTにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET]（https://products.aspose.com/total/net/）を使用すると、.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でTEXファイルをXLTに簡単に変換できます。まず、[Aspose.PDF for .NET]（https://products.aspose.com/pdf/net/）を使用して、TEXをXLSXにエクスポートできます。その後、[Aspose.Cells for .NET]（https://products.aspose.com/cells/net/）Spreadsheet Programming APIを使用して、XLSXをXLTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEXをXLTに変換する.NETAPI" %}}
1. [ドキュメント]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスを使用してTEXファイルを開きます
2. [保存]（https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5）メソッドを使用してTEXをXLSXに変換します
3. [ワークブック]（https://apireference.aspose.com/cells/net/aspose.cells/workbook）クラスを使用してXLSXドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4）メソッドを使用してドキュメントをXLT形式で保存し、「Xlt」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード]（https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたTEXをC＃経由でXLTに変換する" %}}
TEXドキュメントがパスワードで保護されている場合、パスワードなしでXLTに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くには、[Document]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスの新しいインスタンスを初期化し、ファイル名とパスワードを引数として渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して透かし付きのTEXファイルをXLTに変換する" %}}
TEXファイルをXLTに変換するときに、出力XLTファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックオブジェクトを作成し、変換されたXLSXドキュメントを開き、インデックスからワークシートを選択し、シェイプを作成して、AddTextEffect関数を使用します。その後、透かしを使用してXLSXドキュメントをXLTとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-sxc/" name="TEX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xltx/" name="TEX に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-md/" name="TEX に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-tsv/" name="TEX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-txt/" name="TEX に TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-ods/" name="TEX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xlt/" name="TEX に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xlsm/" name="TEX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xlam/" name="TEX に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xltm/" name="TEX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-dif/" name="TEX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xlsb/" name="TEX に XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}