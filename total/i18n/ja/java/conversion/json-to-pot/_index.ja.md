---
title: Javaを介してJSON形式をPOTに変換する
description: Microsoft PowerPointを使用せずに、JavaでJSONをPOTに解析します
url: /ja/java/conversion/json-to-pot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POT
otherformats: POWERPOINT OTP PPTM POTX POTM PPS POT PPSM PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でJSON形式をPOTに変換する" h2="Microsoft <sup>＆reg; </sup>PowerPointを使用せずにJSON形式をPOTに解析するJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を使用すると、2つの簡単な手順で任意のJavaアプリケーション内でJSON形式をPOTに変換できます。まず、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、JSONをPPTXに解析できます。その後、[Aspose.Slides for Java]（https://products.aspose.com/slides/java/）を使用して、PPTXをPOTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java経由でJSON形式をPOTに変換する" %}}
1.新しい[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）オブジェクトを作成し、JSONファイルを開きます
2. [save]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions）を使用してJSONをPPTXとして保存します） 方法
3. [プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用してPPTXドキュメントをロードします
4. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-）メソッドを使用してドキュメントをPOT形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
さらに、APIを使用すると、指定されたレイアウトオプションを使用してJSONからPOTに解析できます。レイアウトオプションを指定するには、[JsonLayoutOptions]（https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions）クラスを使用できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルのスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、Javaを介してJSON形式をPOTに変換する" %}}
APIを使用して、JSONを透かし付きのPOTに変換することもできます。 POTドキュメントに透かしを追加するには、最初にJSONをPPTXに解析し、それに透かしを追加します。透かしを追加するには、[プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用して、新しく作成したPPTXファイルを読み込み、すべてのスライドをループして、テキストを追加しますaddTextFrameを使用して、color、fillTypeなどの関連するすべてのオプションを設定し、ドキュメントをPOTに保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-pps/" name="JSON に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-ppt/" name="JSON に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-pptm/" name="JSON に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-ppsm/" name="JSON に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-powerpoint/" name="JSON に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-pot/" name="JSON に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-potm/" name="JSON に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-otp/" name="JSON に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-ppsx/" name="JSON に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/json-to-potx/" name="JSON に POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}