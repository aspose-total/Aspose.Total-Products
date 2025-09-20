---
title: Javaを介してJSON形式をPPSMに変換する
description: Microsoft PowerPointを使用せずに、JavaでJSONをPPSMに解析します
url_ignore: /ja/java/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: PPS POT POWERPOINT PPSM PPTM POTM PPSX OTP POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でJSON形式をPPSMに変換する" h2="Microsoft<sup>＆reg;</sup>PowerPointを使用せずにJSON形式をPPSMに解析するJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、2つの簡単な手順で任意のJavaアプリケーション内でJSON形式をPPSMに変換できます。まず、[Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用して、JSONをPPTXに解析できます。その後、[Aspose.Slides for Java](https://products.aspose.com/slides/java/)を使用して、PPTXをPPSMに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でJSON形式をPPSMに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)オブジェクトを作成し、JSONファイルを開きます
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)を使用してJSONをPPTXとして保存します) 方法
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをPPSM形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
さらに、APIを使用すると、指定されたレイアウトオプションを使用してJSONからPPSMに解析できます。レイアウトオプションを指定するには、[JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)クラスを使用できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、Javaを介してJSON形式をPPSMに変換する" %}}
APIを使用して、JSONを透かし付きのPPSMに変換することもできます。 PPSMドキュメントに透かしを追加するには、最初にJSONをPPTXに解析し、それに透かしを追加します。透かしを追加するには、[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用して、新しく作成したPPTXファイルを読み込み、すべてのスライドをループして、テキストを追加しますaddTextFrameを使用して、color、fillTypeなどの関連するすべてのオプションを設定し、ドキュメントをPPSMに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSONをPPSMに変換する**ことは、**構造化データからマクロを有効にしたPowerPointスライドショーファイルを作成する**ために不可欠です。PPSMファイルは埋め込みマクロをサポートし、自動インタラクティビティ、ダイナミックコンテンツ、高度なプレゼンテーション機能を可能にします。JSONをPPSMに変換することで、組織は標準化されたインタラクティブなスライドショーを作成し、企業のデモ、トレーニングセッション、データ駆動型のレポーティングを向上させることができます。

{{% blocks/products/pf/agp/feature-section-col title="主要なユースケース" %}}

- **インタラクティブな企業デモ** – クライアントや社内プレゼンテーション向けに埋め込み自動化を備えた魅力的なスライドショーを作成します。
- **自動化されたトレーニングワークフロー** – マクロ駆動のインタラクティビティでオンボーディングや教育セッションを標準化します。
- **データ駆動型ビジネススライドショー** – 構造化データから動的なレポートやダッシュボードを生成します。
- **マーケティングストーリーテリング** – プロモーションキャンペーンや製品ローンチ向けにマクロを有効にしたスライドを作成します。
- **企業レベルの動的レポーティング** – 重複するスライドショーを幹部や部門向けに自動化します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

- **JSONからPPSMへのパイプライン** – 構造化データをマクロを有効にしたスライドショーファイルに自動変換します。
- **自動化されたマクロを有効にしたスライドショーの作成** – 繰り返しの手動スライド制作を排除します。
- **JSON駆動型のインタラクティブデッキ** – 構造化データと動的マクロでスライドショーを作成します。
- **企業全体の動的プレゼンテーション自動化** – チームや部門間でインタラクティブプレゼンテーションをスケールさせます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}