---
title: CGMをODSにレンダリングするJavaAPI
description: MicrosoftExcelまたはAdobeReaderを使用せずにJavaAPIを介してCGMをODSにエクスポートする
url_ignore: /ja/java/conversion/cgm-to-ods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODS
otherformats: XLTM XLSB XLSM XLT SXC MD DIF EXCEL ODS XLAM TXT FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でCGMをODSにエクスポート" h2="Java J2SE、J2EE、J2MEアプリケーション内のオンプレミスJava APIを使用して、CGMファイルをODSに変換します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでCGMからODSへの変換機能を2段階のプロセスで統合できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用して、CGMをXLSXにレンダリングできます。 2番目のステップでは、Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用してXLSXをODSに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でCGMファイルをODSに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してCGMファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してCGMをXLSXに変換します) 方法
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSXドキュメントをロードします
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをODS形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/)あなたのpom.xmlの。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
CGMドキュメントがパスワードで保護されている場合、パスワードなしでODSに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたCGMをJava経由でODSに変換する" %}}
CGMファイルをODSに変換するときに、出力ODSファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたXLSXファイルを開きます。インデックスからワークシートを選択し、図形を作成してそのaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してXLSXドキュメントをODSとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
CGM（Computer Graphics Metafile）ファイルをODS（OpenDocument Spreadsheet）に変換することで、ベクターベースの図と構造化されたデータをオープンソースのスプレッドシート形式で組み合わせることができます。この変換は、表形式のデータと高品質な視覚要素の両方が必要な技術レポート、エンジニアリング文書、および分析タスクにとって重要です。

## ✅ 主な使用シナリオ
- 埋め込み図を含む表形式のエンジニアリングレポートの作成。
- ビジュアル参照を備えたオープンソースプロジェクトのドキュメント。
- ベクターベースのチャートと科学データ分析。
- 統合された図式を使用した製造プロセスの追跡。
- 図形データを含む環境および調査レポート。

## ⚙️ 自動化シナリオ
- JavaベースのETLシステムが組み合わせたデータと図をエクスポート。
- 構造化および視覚的コンテンツのための科学データエクスポートツール。
- マルチフォーマットの技術文書のためのオフィス間の相互運用API。
- 自動化されたデータ可視化パイプライン。
- クロスプラットフォームアクセスのためのLibreOffice Calcとの統合。
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}