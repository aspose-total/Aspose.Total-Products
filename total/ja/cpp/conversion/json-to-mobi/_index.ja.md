---
title: C++を介してJSON形式をMOBIに変換する
description: C++ API t0MicrosoftWordを使用せずにJSONをMOBIに解析する
url: /ja/cpp/conversion/json-to-mobi/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: WORD FLATOPC DOT RTF DOCM WORDML CHM OTT PS DOTX EPUB ODT PCL DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++を介してJSON形式をMOBIに変換する" h2="Microsoft <sup>&reg;</sup>Wordを使用せずにC++アプリケーション内でJSONをMOBIに解析する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)を使用すると、2つの簡単な手順でC++アプリケーション内のJSONをMOBIに解析できます。まず、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用すると、JSONをPDFにエクスポートできます。その後、[Aspose.Words for C++](https://products.aspose.com/words/cppp/)を使用して、PDFをMOBIに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON形式をC++でMOBIに変換する" %}}
1.新しい[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)メソッドを使用してJSONをPDFとして保存します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスを使用してPDFドキュメントをロードします
4. [保存](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メソッドを使用してドキュメントをMOBI形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++でレイアウトを設定してJSON形式をMOBIに変換する" %}}
JSONをMOBIに解析するときに、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスを使用してJSONをロードすることにより、行と列のサイズを設定することもできます。ワークシートのすべての行に同じ行の高さを設定する必要がある場合は、[SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467fを使用して設定できます。 )[ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell)コレクションのメソッド。同様に、ワークシートのすべての列に同じ列幅を設定するには、ICellsコレクションの[SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7)メソッドを使用します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++で透かしを使用してJSON形式をMOBIに変換する" %}}
APIを使用して、透かしを使用してJSONをMOBIに解析することもできます。 MOBIドキュメントに透かしを追加するには、最初にJSONをPDFに変換して、透かしを追加します。透かしを追加するには、[ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスを使用して新しく作成したPDFファイルを読み込み、テキスト透かしにさまざまなプロパティを設定します。
SetTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。透かしを追加した後、ドキュメントをMOBIに保存できます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-word/" name="JSON に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-flatopc/" name="JSON に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-dot/" name="JSON に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-rtf/" name="JSON に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-docm/" name="JSON に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-wordml/" name="JSON に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-mobi/" name="JSON に MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-ott/" name="JSON に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-ps/" name="JSON に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-dotx/" name="JSON に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-epub/" name="JSON に EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-odt/" name="JSON に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-pcl/" name="JSON に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/json-to-doc/" name="JSON に DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}