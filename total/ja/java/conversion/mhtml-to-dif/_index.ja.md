---
title: MHTMLをDIFにレンダリングするJavaAPI
description: MicrosoftExcelまたはAdobeReaderを使用せずにJavaAPIを介してMHTMLをDIFにエクスポートする
url_ignore: /ja/java/conversion/mhtml-to-dif/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DIF
otherformats: XLT TSV EXCEL ODS MD XLSB XLTM DIF XLSM TXT XLTX SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でMHTMLをDIFにエクスポート" h2="Java J2SE、J2EE、J2MEアプリケーション内のオンプレミスJava APIを使用して、MHTMLファイルをDIFに変換します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでMHTMLからDIFへの変換機能を2段階のプロセスで統合できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用して、MHTMLをXLSXにレンダリングできます。 2番目のステップでは、Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用してXLSXをDIFに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でMHTMLファイルをDIFに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してMHTMLファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してMHTMLをXLSXに変換します) 方法
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSXドキュメントをロードします
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをDIF形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/)あなたのpom.xmlの。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
MHTMLドキュメントがパスワードで保護されている場合、パスワードなしでDIFに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたMHTMLをJava経由でDIFに変換する" %}}
MHTMLファイルをDIFに変換するときに、出力DIFファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたXLSXファイルを開きます。インデックスからワークシートを選択し、図形を作成してそのaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してXLSXドキュメントをDIFとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



MHTMLからDIF（Data Interchange Format）への変換により、Webベースの表形式データを旧式のスプレッドシートアプリケーションや特殊な統計ツールにインポートできます。DIFは、プラットフォーム間で構造化されたポータブルなデータセットを確保します。



{{% blocks/products/pf/agp/feature-section-col title="主な使用事例" %}}



* 歴史的なWebデータを統計解析ソフトウェアにインポートする。

* 互換性のないオフィススイート間で表形式のWebコンテンツを共有する。

* オンライン調査データを学術研究用のDIFに変換する。

* コンプライアンスのために企業のWebベースのダッシュボードをアーカイブする。



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}



* 旧式のレポーティングシステム向けの定期的なDIF変換。

* クロスプラットフォームワークフロー向けのWebテーブルの一括変換。

* 定期的な調査データの更新のための自動化されたDIF抽出。

* アーカイブおよび監査目的のトリガー付きDIF生成。



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}