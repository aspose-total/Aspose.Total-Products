---
title: C＃APIを介してCGMをTSVに変換する
description: MicrosoftExcelまたはAdobeReaderを使用せずにCGMファイルをTSVに変換するC＃API
url_ignore: /ja/net/conversion/cgm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TSV
otherformats: TSV FODS XLSM EXCEL TXT SXC XLAM ODS DIF XLSB XLT MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGMをTSVにレンダリングするC＃API" h2="Microsoft<sup>＆reg;</sup>ExcelまたはAdobe<sup>＆reg;</sup> Acrobat Readerを使用せずにC＃経由でCGMファイルをTSVにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でCGMファイルをTSVに簡単に変換できます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用して、CGMをXLSXにエクスポートできます。その後、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)Spreadsheet Programming APIを使用して、XLSXをTSVに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをTSVに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをXLSXに変換します
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLSXドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)メソッドを使用してドキュメントをTSV形式で保存し、「Tsv」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたCGMをC＃経由でTSVに変換する" %}}
CGMドキュメントがパスワードで保護されている場合、パスワードなしでTSVに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスの新しいインスタンスを初期化し、ファイル名とパスワードを引数として渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して透かし付きのCGMファイルをTSVに変換する" %}}
CGMファイルをTSVに変換するときに、出力TSVファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックオブジェクトを作成し、変換されたXLSXドキュメントを開き、インデックスからワークシートを選択し、シェイプを作成して、AddTextEffect関数を使用します。その後、透かしを使用してXLSXドキュメントをTSVとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをTSVに変換する：ユースケース" %}}
CGMファイルをTSVフォーマットに変換する必要があります。これにより、データ分析の潜力を最大限度発揮することが可能になります。

**用途:**

* **データ統合**: CGMファイルをTSVフォーマットに変換し、他のデータソースやツールとのシームレスな統合が可能になります。
* **機械学習モデル訓練**: TSV形式のデータを使用して機械学習モデルのトレーニングを行うことができるため、正確な予測と洞察を得ることができます。
* **ビジネスインテリジェンスレポート**: CGMファイルをTSVフォーマットに変換し、インタクティブなダッシュボードやレポートを作成することができるため、better decision-makingを支援します。
* **データマイ닝と分析**: TSV形式のデータを使用してデータマイ닝や分析を行うことができるため、パターン、トレンド、コレレーションを識別することができます。
* **クラウドストレージへのアップロード**: CGMファイルをTSVフォーマットに変換し、AWS S3やGoogle Cloud Storageなどのクラウドストレージサービスに容易にアップロードすることができるため。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}