---
title: C＃APIを介してCGMをMDに変換する
description: MicrosoftExcelまたはAdobeReaderを使用せずにCGMファイルをMDに変換するC＃API
url_ignore: /ja/net/conversion/cgm-to-md/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MD
otherformats: TXT ODS EXCEL SXC DIF XLTX XLSM TSV MD XLTM XLAM XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGMをMDにレンダリングするC＃API" h2="Microsoft<sup>＆reg;</sup>ExcelまたはAdobe<sup>＆reg;</sup> Acrobat Readerを使用せずにC＃経由でCGMファイルをMDにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、.NET、C＃、ASP.NET、およびVB.NETアプリケーション内でCGMファイルをMDに簡単に変換できます。まず、[Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用して、CGMをXLSXにエクスポートできます。その後、[Aspose.Cells for .NET](https://products.aspose.com/cells/net/)Spreadsheet Programming APIを使用して、XLSXをMDに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをMDに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをXLSXに変換します
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLSXドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)メソッドを使用してドキュメントをMD形式で保存し、「Md」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたCGMをC＃経由でMDに変換する" %}}
CGMドキュメントがパスワードで保護されている場合、パスワードなしでMDに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスの新しいインスタンスを初期化し、ファイル名とパスワードを引数として渡すことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C＃を介して透かし付きのCGMファイルをMDに変換する" %}}
CGMファイルをMDに変換するときに、出力MDファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックオブジェクトを作成し、変換されたXLSXドキュメントを開き、インデックスからワークシートを選択し、シェイプを作成して、AddTextEffect関数を使用します。その後、透かしを使用してXLSXドキュメントをMDとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをMDに変換する：ユースケース" %}}
CGM ファイルのフォーマットをMarkdown（MD）に変換する必要があります。これにより、自分の文書能力を最大限発揮することが可能になります。

**用途：**

* **技術情報のドキュメント作成**：CGM ファイルを Markdown でユーザーマニュアル、技術ガイド、ソフトウェア、アプリケーション、複合システム向けのドキュメンテーションを作成する。
* **デザインコンセプトの共有**：Markdown を用いてデザインコンセプトを視覚化し、製品の特徴を説明し、設計プロジェクトで利益相反する関係者と協力する。
* **インタラクティブコンテンツの作成**：CGM ファイルを Markdown に変換して、チュートリアル、シミュレーション、体験的な内容を作成し、製品、サービスの活性を示す。
* **技術ブログの執筆**：Markdown を用いてソフトウェア開発、プロダクトマネージメント、業界のトレンドについての技術記事やガイドを執筆し、公開する。
* **知識ベース記事の作成**：CGM ファイルを Markdown に変換して、ユーザー、従業員、パートナー向けにわたる完全な知識ベース記事、指南、FAQを作成する。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}