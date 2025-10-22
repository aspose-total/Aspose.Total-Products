---
title: PSをTSVにレンダリングするJavaAPI
description: MicrosoftExcelまたはAdobeReaderを使用せずにJavaAPIを介してPSをTSVにエクスポートする
url_ignore: /ja/java/conversion/ps-to-tsv/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: TSV
otherformats: FODS ODS EXCEL XLSB TXT DIF XLSM TSV XLAM SXC MD XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でPSをTSVにエクスポート" h2="Java J2SE、J2EE、J2MEアプリケーション内のオンプレミスJava APIを使用して、PSファイルをTSVに変換します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでPSからTSVへの変換機能を2段階のプロセスで統合できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用して、PSをXLSXにレンダリングできます。 2番目のステップでは、Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用してXLSXをTSVに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でPSファイルをTSVに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してPSファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してPSをXLSXに変換します) 方法
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSXドキュメントをロードします
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをTSV形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/)あなたのpom.xmlの。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
PSドキュメントがパスワードで保護されている場合、パスワードなしでTSVに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたPSをJava経由でTSVに変換する" %}}
PSファイルをTSVに変換するときに、出力TSVファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたXLSXファイルを開きます。インデックスからワークシートを選択し、図形を作成してそのaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してXLSXドキュメントをTSVとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

PS（PostScript）ファイルをTSV（Tab-Separated Values）に変換することは、ビジネスインテリジェンス、統計、エンジニアリングシステム間のデータ交換を標準化するのに役立ちます。TSVは、構造化されたが人間が読みやすい形式を提供し、PSのレイアウトから抽出されたデータを分析パイプラインに移行するのに最適です。

{{% blocks/products/pf/agp/feature-section-col title="主な使用ケース" %}}

* PSフォームから構造化されたテキストやデータをTSVに変換して処理する。
* 統計ツール向けに科学的または実験的結果をエクスポートする。
* PostScriptベースのドキュメントから表形式のコンテンツをオープンデータ形式に変換する。
* R、Python、またはMATLAB環境との互換性を持つデータセットを準備する。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* データウェアハウスシステムでの自動化されたPSからTSVへの変換。
* 構造化データ移行のためのETLツールとの統合。
* PSベースのレポートエンジンからの定期的な抽出ワークフロー。
* ビッグデータ分析のためのクラウドベースのPSドキュメント処理。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}