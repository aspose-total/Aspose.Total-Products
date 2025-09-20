---
title: Javaを介してJSON形式をPPSに変換する
description: Microsoft PowerPointを使用せずに、JavaでJSONをPPSに解析します
url_ignore: /ja/java/conversion/json-to-pps/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPS
otherformats: POT PPTM PPSM POTM OTP POWERPOINT PPSX PPS PPT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でJSON形式をPPSに変換する" h2="Microsoft<sup>＆reg;</sup>PowerPointを使用せずにJSON形式をPPSに解析するJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を使用すると、2つの簡単な手順で任意のJavaアプリケーション内でJSON形式をPPSに変換できます。まず、[Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用して、JSONをPPTXに解析できます。その後、[Aspose.Slides for Java](https://products.aspose.com/slides/java/)を使用して、PPTXをPPSに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でJSON形式をPPSに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)オブジェクトを作成し、JSONファイルを開きます
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)を使用してJSONをPPTXとして保存します) 方法
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをPPS形式で保存します
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
さらに、APIを使用すると、指定されたレイアウトオプションを使用してJSONからPPSに解析できます。レイアウトオプションを指定するには、[JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)クラスを使用できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、Javaを介してJSON形式をPPSに変換する" %}}
APIを使用して、JSONを透かし付きのPPSに変換することもできます。 PPSドキュメントに透かしを追加するには、最初にJSONをPPTXに解析し、それに透かしを追加します。透かしを追加するには、[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用して、新しく作成したPPTXファイルを読み込み、すべてのスライドをループして、テキストを追加しますaddTextFrameを使用して、color、fillTypeなどの関連するすべてのオプションを設定し、ドキュメントをPPSに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSONをPPSに変換**することは、**構造化されたデータから直接PowerPointスライドショーファイルを作成**するために不可欠です。PPSファイルはフルスクリーンのスライドショーとして開き、自動プレゼンテーション配信、インタラクティブなデモ、一貫した企業や教育プレゼンテーションに最適です。JSONをPPSに変換することで、組織はスライドの制作を効率化し、手動の書式設定を削減し、標準化されたスライドショーの出力を確保できます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用シナリオ" %}}

- **自動スライドショー配信** – 会議やオンライン配信用の再生準備が整ったプレゼンテーションを生成します。
- **マーケティングデモ** – 製品プロモーションやキャンペーン用のインタラクティブなスライドショーを制作します。
- **トレーニングセッション** – 教育やオンボーディングプレゼンテーションを規模化して標準化します。
- **会議プレゼンテーション** – イベントやセミナー用に一貫した、プロフェッショナルなデッキを提供します。
- **データストーリーテリング** – 構造化されたデータセットを視覚的に魅力的なスライドナラティブに変換します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

- **JSONからPPSへのパイプライン** – 構造化されたデータセットからスライドショーファイルの作成を自動化します。
- **自動スライドショー生成** – 繰り返しのプレゼンテーションのデザインにおける手動作業を削減します。
- **企業全体にわたるデッキ配信** – 部門やチーム全体に標準化されたスライドを配布します。
- **JSON統合型プレゼンテーション自動化** – 動的データをスライドに埋め込んでリアルタイムの可視化を行います。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}