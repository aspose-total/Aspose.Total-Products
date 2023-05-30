---
title: Javaを介してAndroidでJSON形式をPCLに変換する
description: MicrosoftWordを使用せずにJavaでJSONをPCLに解析する

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PCL
otherformats: DOCM OTT ODT WORD WORDML DOT DOC MOBI PS DOTX EPUB CHM RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndroidアプリケーションでJSON形式をPCLに変換する" h2="Microsoft <sup>&reg;</sup> Wordを使用せずに、Androidアプリケーション内でJSONをPCLに解析します" >}}

{{% blocks/products/pf/feature-page-summary %}}
AndroidアプリケーションでJSONをPCLに2段階のプロセスで変換できます。まず、強力なスプレッドシート処理API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用して、JSONをPDFに解析できます。 2番目のステップでは、ワードプロセッシングAPI [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用してPDFをPCLに変換できます。どちらのAPIも、[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)製品ファミリーに分類されます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してAndroidでJSON形式をPCLに変換する" %}}
1. しい[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility)クラスと[Save](https://reference.aspose.com/)を使用して、JSONファイルをワークシートにインポートします。 cells / java / com.aspose.cells / workbook＃save（java.lang.String、％20com.aspose.cells.SaveOptions))PDFとして
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してPDFドキュメントをロードします
4. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをPCL形式で保存します)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。アプリにライブラリをインストールします。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidでレイアウトを設定してJSON形式をPCLに変換する" %}}
さらに、APIを使用すると、[JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions)を使用してJSONをPCLに解析しながら、JSON形式のレイアウトオプションを設定できます。これにより、配列をテーブルとして処理し、nullを無視し、配列のタイトルを無視し、オブジェクトのタイトルを無視し、文字列を数値または日付に変換し、日付と数値の形式を設定し、タイトルスタイルを設定できます。これらのオプションはすべて、必要に応じてデータを表示できます。次のコードスニペットは、レイアウトオプションを設定する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java経由でAndroidの透かしを使用してJSON形式をPCLに変換する" %}}
APIを使用して、JSONを透かし付きのPCLに変換することもできます。 PCLドキュメントに透かしを追加するには、最初にJSONファイルをPDFに解析し、それに透かしを追加します。透かしを追加するには、[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用して新しく作成したPDFファイルをロードし、TextWatermarkOptionsのインスタンスを作成して設定します。そのプロパティ、Watermark.setTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。透かしを追加した後、ドキュメントをPCLに保存できます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}