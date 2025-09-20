---
title: Java経由でJSON形式をCHMに変換する
description: MicrosoftWordを使用せずにJavaでJSONをCHMに解析する
url_ignore: /ja/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でJSON形式をCHMに変換する" h2="Microsoft<sup>＆reg;</sup>Wordを使用せずにJSONをCHMに解析するオンプレミスのJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、JavaアプリケーションでJSONをCHMに2段階のプロセスで変換できます。まず、[Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用して、JSONをPDFに解析できます。 2番目のステップでは、ワードプロセッシングAPI [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してPDFをCHMに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でJSON形式をCHMに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility)クラスと[Save](https://reference.aspose.com/)を使用して、JSONファイルをワークシートにインポートします。 cells / java / com.aspose.cells / workbook＃save(java.lang.String、％20com.aspose.cells.SaveOptions))PDF形式で表示
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してPDFドキュメントをロードします
4. [Document.save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) 方法 を使用してドキュメントをCHM形式で保存します
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
さらに、APIを使用すると、[JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)を使用してJSONをCHMに解析しながら、JSONのレイアウトオプションを設定できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、Javaを介してJSON形式をCHMに変換する" %}}
APIを使用して、透かしを使用してJSONからCHMに解析することもできます。 CHMドキュメントに透かしを追加するには、最初にJSONファイルをPDFに変換し、それに透かしを追加します。透かしを追加するには、[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用して新しく作成したPDFファイルをロードし、TextWatermarkOptionsのインスタンスを作成して設定します。そのプロパティ、Watermark.setTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。透かしを追加した後、ドキュメントをCHMに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSONをCHM（コンパイル済みHTMLヘルプ）に変換**することは、**構造化されたドキュメントから直接コンパイルされたヘルプマニュアル**を作成するために不可欠です。CHMファイルは複数のヘルプトピックを1つの検索可能でオフラインアクセス可能なリソースに組み合わせ、ソフトウェアサポートや企業の知識管理に最適です。JSONをCHMに変換することで、組織はドキュメント配信を効率化し、使いやすさを向上させ、インターネット接続なしでもアクセス可能性を確保できます。

{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}

- **ソフトウェアドキュメント** – テクニカルガイドをコンパイルされた使いやすい形式にパッケージ化します。
- **オフラインヘルプシステム** – インターネットアクセスを必要とせずにドキュメントを提供します。
- **企業の知識ベース** – 組織の知識を構造化されたヘルプファイルに集約します。
- **トレーニングマニュアル** – スタッフや学生向けにコンパイルされた学習リソースを配布します。
- **開発者APIリファレンス** – 構造化されたJSON定義を検索可能なオフラインリファレンスに変換します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

- **JSONからCHMへのパイプライン** – 構造化データをコンパイルされたヘルプマニュアルに自動変換します。
- **自動化されたヘルプファイル作成** – 進化するJSONベースのコンテンツから直接CHMファイルを生成します。
- **データからドキュメントへのコンパイル** – 構造化されたJSONドキュメントをアクセス可能なヘルプシステムに変換します。
- **オフライン知識配布** – 企業全体のトレーニングとサポートのためにCHMマニュアルを標準化します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}