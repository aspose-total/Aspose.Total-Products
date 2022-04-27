---
title: C＃APIを介してSVGをMDに変換する
description: MicrosoftExcelまたはAdobeReaderを使用せずにSVGファイルをMDに変換するC＃API
url: /ja/net/conversion/svg-to-md/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: MD
otherformats: EXCEL XLSM MD XLTX SXC FODS XLSB ODS TSV TXT DIF XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="SVGをMDにレンダリングするC＃API" h2="Microsoft<sup>＆reg;</sup>ExcelまたはAdobe<sup>＆reg;</sup> Acrobat Readerを使用せずにC＃経由でSVGファイルをMDにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET]（https://products.aspose.com/total/net/）を使用すると、.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でSVGファイルをMDに簡単に変換できます。まず、[Aspose.PDF for .NET]（https://products.aspose.com/pdf/net/）を使用して、SVGをXLSXにエクスポートできます。その後、[Aspose.Cells for .NET]（https://products.aspose.com/cells/net/）Spreadsheet Programming APIを使用して、XLSXをMDに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SVGをMDに変換する.NETAPI" %}}
1. [ドキュメント]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスを使用してSVGファイルを開きます
2. [保存]（https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5）メソッドを使用してSVGをXLSXに変換します
3. [ワークブック]（https://apireference.aspose.com/cells/net/aspose.cells/workbook）クラスを使用してXLSXドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4）メソッドを使用してドキュメントをMD形式で保存し、「Md」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード]（https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたSVGをC＃経由でMDに変換する" %}}
SVGドキュメントがパスワードで保護されている場合、パスワードなしでMDに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くには、[Document]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスの新しいインスタンスを初期化し、ファイル名とパスワードを引数として渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して透かし付きのSVGファイルをMDに変換する" %}}
SVGファイルをMDに変換するときに、出力MDファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックオブジェクトを作成し、変換されたXLSXドキュメントを開き、インデックスからワークシートを選択し、シェイプを作成して、AddTextEffect関数を使用します。その後、透かしを使用してXLSXドキュメントをMDとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-sxc/" name="SVG に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xltx/" name="SVG に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-md/" name="SVG に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-tsv/" name="SVG に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-txt/" name="SVG に TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-ods/" name="SVG に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xlt/" name="SVG に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xlsm/" name="SVG に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xlam/" name="SVG に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xltm/" name="SVG に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-dif/" name="SVG に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xlsb/" name="SVG に XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}