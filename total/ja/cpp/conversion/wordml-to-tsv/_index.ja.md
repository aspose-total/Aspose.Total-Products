---
title: C++でWORDMLをTSVに変換する
description: MicrosoftWordまたはMicrosoftExcelを使用せずにWORDMLをTSVに変換するC++API

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: TSV
otherformats: CSV XLSB ODS XLTX XLTM SXC XLS XLSX XLSM FODS XLAM EXCEL DIF XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORDMLをTSVに変換するC++API" h2="Microsoft <sup>&reg;</sup>WordまたはMicrosoft<sup>&reg;</sup>Excelを使用せずにC++経由でWORDMLをTSVにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++アプリケーションにWORDMLからTSVへの変換機能を簡単に含めることができます。機能豊富で強力で使いやすいドキュメント操作および変換API[Aspose.Wordsfor C++](https://products.aspose.com/words/cpp/)を使用することで、WORDMLをHTMLにエクスポートできます。その後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用して、HTMLをTSVに変換できます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDMLをTSVに変換するC++API" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)クラスリファレンスを使用してWORDMLファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string_saveformat)メンバー関数を使用してWORDMLをHTMLに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)メンバー関数を使用してドキュメントをTSV形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++経由でWORDMLドキュメントのプロパティにアクセスする" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)では、WORDMLファイルのドキュメントプロパティにアクセスし、変換プロセスの前に十分な情報に基づいて決定を下すことができます。ドキュメントのプロパティにアクセスするには、[BuiltInWordmlumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordmlument_properties)を使用して、組み込みのプロパティと[CustomWordmlumentProperties](https：// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_wordmlument_properties)を使用して、カスタムプロパティを取得します。次のコード例は、ドキュメント内のすべての組み込みプロパティとカスタムプロパティを列挙する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordmlument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="TSVファイルをC++経由でストリームに保存" %}}
WORDMLをTSVに変換した後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用すると、ドキュメントをストリーミングに保存できます。ファイルをストリームに保存するには、MemoryStreamまたはFileStreamオブジェクトを作成し、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を呼び出してファイルをそのストリームオブジェクトに保存します。オブジェクトの[Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349)メソッド。 [Save](https://reference.aspose.com)を呼び出すときに、[SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a)列挙を使用して目的のファイル形式を指定します。メソッド。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-tsv/" name="WORDML に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xlsb/" name="WORDML に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-ods/" name="WORDML に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xltx/" name="WORDML に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xltm/" name="WORDML に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-sxc/" name="WORDML に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xls/" name="WORDML に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xlsx/" name="WORDML に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xlsm/" name="WORDML に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-fods/" name="WORDML に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xlam/" name="WORDML に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-excel/" name="WORDML に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-dif/" name="WORDML に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/wordml-to-xlt/" name="WORDML に XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}