---
title: MDをTXTにレンダリングするJavaAPI
description: MicrosoftExcelまたはAdobeReaderを使用せずにJavaAPIを介してMDをTXTにエクスポートする
url_ignore: /ja/java/conversion/md-to-txt/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TXT
otherformats: ODS XLT XLTM XLSM TXT FODS XLTX XLSB DIF XLAM TSV EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でMDをTXTにエクスポート" h2="Java J2SE、J2EE、J2MEアプリケーション内のオンプレミスJava APIを使用して、MDファイルをTXTに変換します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでMDからTXTへの変換機能を2段階のプロセスで統合できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用して、MDをXLSXにレンダリングできます。 2番目のステップでは、Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用してXLSXをTXTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でMDファイルをTXTに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してMDファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してMDをXLSXに変換します) 方法
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSXドキュメントをロードします
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをTXT形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/)あなたのpom.xmlの。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
MDドキュメントがパスワードで保護されている場合、パスワードなしでTXTに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたMDをJava経由でTXTに変換する" %}}
MDファイルをTXTに変換するときに、出力TXTファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたXLSXファイルを開きます。インデックスからワークシートを選択し、図形を作成してそのaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してXLSXドキュメントをTXTとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Markdown（MD）ファイルをTXT（プレーンテキスト）に変換すると、フォーマットやマークアップが削除されたクリーンで軽量なコンテンツが生成されます。TXTファイルは高い互換性を持ち、テキスト処理、スクリプティング、Markdownフォーマットをサポートしていないアプリケーションとの統合に最適です。



{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}



* プレーンテキストの電子メール配信用にMarkdownドキュメントをエクスポートする。

* テキストベースの分析や機械学習ワークフロー用の生データを生成する。

* メモやドキュメントの軽量でポータブルなコピーを作成する。

* リッチなフォーマットがサポートされていない環境でのMarkdownコンテンツの共有。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}



* MarkdownリポジトリをTXTにバックアップおよびアーカイブ用に定期的にバッチ変換する。

* ETLパイプラインを使用してMarkdownドキュメントをTXTに変換し、スクリプトや自動化ツールで処理する。

* Markdownベースのプロジェクトノートからプレーンテキストログを自動生成する。

* MarkdownをTXTとしてエクスポートするためのコンテンツパイプラインとの統合。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}