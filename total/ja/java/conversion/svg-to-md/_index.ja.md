---
title: SVGをMDにレンダリングするJavaAPI
description: MicrosoftExcelまたはAdobeReaderを使用せずにJavaAPIを介してSVGをMDにエクスポートする
url_ignore: /ja/java/conversion/svg-to-md/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: MD
otherformats: XLT SXC XLTM XLSB ODS MD EXCEL XLTX DIF TSV TXT XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でSVGをMDにエクスポート" h2="Java J2SE、J2EE、J2MEアプリケーション内のオンプレミスJava APIを使用して、SVGファイルをMDに変換します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでSVGからMDへの変換機能を2段階のプロセスで統合できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用して、SVGをXLSXにレンダリングできます。 2番目のステップでは、Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用してXLSXをMDに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でSVGファイルをMDに変換する" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してSVGファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してSVGをXLSXに変換します) 方法
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSXドキュメントをロードします
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをMD形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/)あなたのpom.xmlの。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
SVGドキュメントがパスワードで保護されている場合、パスワードなしでMDに変換することはできません。 APIを使用すると、最初に有効なパスワードを使用して保護されたドキュメントを開き、その後変換することができます。暗号化されたファイルを開くために、の新しいインスタンスを初期化できます[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-)クラスを作成し、ファイル名とパスワードを引数として渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたSVGをJava経由でMDに変換する" %}}
SVGファイルをMDに変換するときに、出力MDファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたXLSXファイルを開きます。インデックスからワークシートを選択し、図形を作成してそのaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してXLSXドキュメントをMDとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

SVGをMarkdown（MD）に変換すると、ベクターダイアグラムをドキュメント、READMEファイル、静的サイトジェネレータに直接埋め込むことができます。このアプローチは、グラフィックを軽量化し、完全にスケーラブルに保ちながら技術コンテンツの読みやすさを向上させます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用用途" %}}

* ソフトウェアプロジェクトのREADMEファイルにアーキテクチャ図を埋め込む。
* オープンソースのドキュメントリポジトリ用のインタラクティブなフローチャート。
* インラインベクターイラストを使用したMarkdownベースの電子書籍やチュートリアル。
* 余分な画像ファイルなしでクリーンでスケーラブルな視覚要素を使用した技術ブログ。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* ドキュメントパイプライン用の自動化されたSVGからMDへの変換。
* ナレッジベースの更新のためのベクターダイアグラムの定期的な生成。
* HugoやJekyllなどの静的サイトジェネレータとの統合。
* デザインの更新をMarkdown技術ファイルに連続的に同期。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}