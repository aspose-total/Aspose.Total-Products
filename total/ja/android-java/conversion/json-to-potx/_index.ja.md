---
title: Javaを介してAndroidでJSON形式をPOTXに変換する
description: MicrosoftPowerPointを使用せずにAndroidアプリケーションでJSONをPOTXに解析する

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX PPTM POWERPOINT POT POTM ODP PPSM OTP PPS PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndroidでJSON形式をPOTXに変換する" h2="Microsoft <sup>&reg;</sup> PowerPointを使用せずに、AndroidアプリケーションでJSON形式をPOTXに解析する" >}}

{{% blocks/products/pf/feature-page-summary %}}
AndroidアプリケーションでJSON形式をPOTXに2段階のプロセスで変換できます。まず、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用すると、JSONをPPTXに解析できます。その後、[Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)を使用して、PPTXをPOTXに変換できます。どちらのAPIも、[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでJSON形式をPOTXに変換する" %}}
1. しい[ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)オブジェクトを作成し、JSONファイルを開きます
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)を使用してJSONをPPTXとして保存します) 方法
3. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTXドキュメントをロードします
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)メソッドを使用してドキュメントをPOTX形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。アプリにライブラリをインストールします。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Androidアプリケーションでレイアウトを設定してJSON形式をPOTXに変換する" %}}
さらに、APIを使用すると、指定したレイアウトオプションを使用してJSONをPOTXに解析できます。レイアウトオプションを指定するには、[JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)クラスを使用できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java経由でAndroidの透かしを使用してJSON形式をPOTXに変換する" %}}
APIを使用して、JSONを透かし付きのPOTXに変換することもできます。 POTXドキュメントに透かしを追加するには、最初にJSONをPPTXに解析して、透かしを追加します。透かしを追加するには、[プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用して、新しく作成したPPTXファイルを読み込み、すべてのスライドをループして、テキストを追加します。 addTextFrameを使用して、color、fillTypeなどの関連するすべてのオプションを設定し、ドキュメントをPOTXに保存できます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}