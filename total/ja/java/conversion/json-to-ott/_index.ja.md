---
title: Java経由でJSON形式をOTTに変換する
description: MicrosoftWordを使用せずにJavaでJSONをOTTに解析する
url_ignore: /ja/java/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: DOC WORD MOBI RTF DOCM EPUB ODT OTT PS WORDML DOT PCL FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でJSON形式をOTTに変換する" h2="Microsoft<sup>＆reg;</sup>Wordを使用せずにJSONをOTTに解析するオンプレミスのJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでJSONをOTTに2段階のプロセスで変換できます。まず、[Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用して、JSONをPDFに解析できます。 2番目のステップでは、ワードプロセッシングAPI [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してPDFをOTTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でJSON形式をOTTに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility)クラスと[Save](https://reference.aspose.com/)を使用して、JSONファイルをワークシートにインポートします。 cells / java / com.aspose.cells / workbook＃save(java.lang.String、％20com.aspose.cells.SaveOptions))PDF形式で表示
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してPDFドキュメントをロードします
4. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをOTT形式で保存します)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
さらに、APIを使用すると、[JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)を使用してJSONをOTTに解析しながら、JSONのレイアウトオプションを設定できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、Javaを介してJSON形式をOTTに変換する" %}}
APIを使用して、透かしを使用してJSONからOTTに解析することもできます。 OTTドキュメントに透かしを追加するには、最初にJSONファイルをPDFに変換し、それに透かしを追加します。透かしを追加するには、[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用して新しく作成したPDFファイルをロードし、TextWatermarkOptionsのインスタンスを作成して設定します。そのプロパティ、Watermark.setTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。透かしを追加した後、ドキュメントをOTTに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
JSONをOTTに変換することは、構造化されたデータセットから**テキストドキュメントテンプレート**を生成するために不可欠です。OTT、OpenDocument Text Template形式は、LibreOfficeやOpenOfficeなどのオープンソースオフィススイートで再利用可能で編集可能なテンプレートを作成する標準化された方法を提供します。JSONをOTTに変換することで、組織は複数のワークフロー全体で文書生成に一貫性、コンプライアンス、自動化を確保します。

{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}

- **政府文書フレームワーク** – 公式使用の標準化されたフォームやレポートを作成します。
- **法的テンプレート** – 契約書、合意書、コンプライアンス対応フォーマットを自動化します。
- **ビジネスレター** – 企業間のやり取りに一貫性を保ちます。
- **教育用レポート** – 研究や課題のための学術用ドキュメントテンプレートを生成します。
- **オープンソースオフィス統合** – オープンソース環境でJSON駆動のテンプレートをシームレスに使用します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

- **JSONからOTTへのパイプライン** – 構造化されたJSONデータセットからのテンプレート作成を自動化します。
- **自動化されたテンプレートワークフロー** – 部門全体での手動フォーマット作業を削減します。
- **JSON駆動の文書生成** – 企業の報告書やコンプライアンスに一貫性を強制します。
- **企業向けテンプレート配布** – グローバルチーム全体で文書テンプレートを標準化します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}