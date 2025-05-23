---
title: C＃APIを介してCGMをEXCELに変換する
description: MicrosoftExcelまたはAdobeReaderを使用せずにCGMファイルをEXCELに変換するC＃API
url_ignore: /ja/net/conversion/cgm-to-excel/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: EXCEL
otherformats: XLTX XLSB TXT ODS XLTM EXCEL DIF XLAM XLT MD SXC TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGMをEXCELにレンダリングするC＃API" h2="Microsoft<sup>＆reg;</sup>ExcelまたはAdobe<sup>＆reg;</sup> Acrobat Readerを使用せずにC＃経由でCGMファイルをEXCELにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でCGMファイルをEXCELに簡単に変換できます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用して、CGMをXLSXにエクスポートできます。その後、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)Spreadsheet Programming APIを使用して、XLSXをEXCELに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをEXCELに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをXLSXに変換します
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLSXドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)メソッドを使用してドキュメントをEXCEL形式で保存し、「Excel」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたCGMをC＃経由でEXCELに変換する" %}}
CGMドキュメントがパスワードで保護されている場合、パスワードなしでEXCELに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスの新しいインスタンスを初期化し、ファイル名とパスワードを引数として渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して透かし付きのCGMファイルをEXCELに変換する" %}}
CGMファイルをEXCELに変換するときに、出力EXCELファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックオブジェクトを作成し、変換されたXLSXドキュメントを開き、インデックスからワークシートを選択し、シェイプを作成して、AddTextEffect関数を使用します。その後、透かしを使用してXLSXドキュメントをEXCELとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをEXCELに変換する：ユースケース" %}}
**CGM (コンピュータグラフィックスメタファイル) ファイルは、ダイナミックなデータビジュアライズにとって理想的ではない**

CGM ファイルは、ベクター グラフィックス情報を保存するために使用されますが、その用途は静的なグラフィックスやイラストレーションに限られます。動きがあるデータの場合には、スプレッドシートであるExcel が不可欠なデータ ビジュアライズと分析のためのツールとなります。

CGM ファイルを Excel 形式に変換する必要があります。これにより、データ ビジュアライズや分析の可能性を完全に引き出すことができます。この変換によって以下のような用途が実現されます：

**用途:**

* **ダイナミックなデータ アнаリза:** CGM ファイルを Excel 形式に変換し、ダイナミックなデータを分析し、トレンドを識別し、パフォーマンスを最適化することができます。
* **リアルタイム ビジュアライズ:** Excel を使用してリアルタイムのデータを視覚化し、迅速な决策-making とより正確な洞察を実現することができます。
* **コラボレーションツール:** CGM ファイルを Excel 形式に変換し、interactive ダッシュボード、レポート、ビジュアライズを作成し、チームでの協力とステークホルダーとのエンゲージ먼트을 실현することができます。
* **高度な科学的モデリング:** Excel を使用して複雑な科学現象をモデル化し、実験のシミュレーションを行い、仮説を検証することができます。
* **ビッグデータ プロセッサ:** CGM ファイルを Excel 形式に変換し、大規模なデータセットをプロセッすことでパターンを識別し、有価なインスाइटを得ることができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}