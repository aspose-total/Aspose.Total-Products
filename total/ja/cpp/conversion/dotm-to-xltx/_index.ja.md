---
title: C++でDOTMをXLTXに変換する
description: MicrosoftWordまたはMicrosoftExcelを使用せずにDOTMをXLTXに変換するC++API
url: /ja/cpp/conversion/dotm-to-xltx/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLTX
otherformats: DIF EXCEL XLS FODS XLSX CSV ODS TSV XLTM XLT XLSM XLAM SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="DOTMをXLTXに変換するC++API" h2="Microsoft <sup>&reg;</sup>WordまたはMicrosoft<sup>&reg;</sup>Excelを使用せずにC++経由でDOTMをXLTXにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++アプリケーションにDOTMからXLTXへの変換機能を簡単に含めることができます。機能豊富で強力で使いやすいドキュメント操作および変換API[Aspose.Wordsfor C++](https://products.aspose.com/words/cpp/)を使用することで、DOTMをHTMLにエクスポートできます。その後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用して、HTMLをXLTXに変換できます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTMをXLTXに変換するC++API" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)クラスリファレンスを使用してDOTMファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string_saveformat)メンバー関数を使用してDOTMをHTMLに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)メンバー関数を使用してドキュメントをXLTX形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++経由でDOTMドキュメントのプロパティにアクセスする" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)では、DOTMファイルのドキュメントプロパティにアクセスし、変換プロセスの前に十分な情報に基づいて決定を下すことができます。ドキュメントのプロパティにアクセスするには、[BuiltInDotmumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotmument_properties)を使用して、組み込みのプロパティと[CustomDotmumentProperties](https：// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotmument_properties)を使用して、カスタムプロパティを取得します。次のコード例は、ドキュメント内のすべての組み込みプロパティとカスタムプロパティを列挙する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotmument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLTXファイルをC++経由でストリームに保存" %}}
DOTMをXLTXに変換した後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用すると、ドキュメントをストリーミングに保存できます。ファイルをストリームに保存するには、MemoryStreamまたはFileStreamオブジェクトを作成し、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を呼び出してファイルをそのストリームオブジェクトに保存します。オブジェクトの[Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349)メソッド。 [Save](https://reference.aspose.com)を呼び出すときに、[SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a)列挙を使用して目的のファイル形式を指定します。メソッド。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-dif/" name="DOTM に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-excel/" name="DOTM に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xls/" name="DOTM に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-fods/" name="DOTM に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xlsx/" name="DOTM に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xltx/" name="DOTM に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-ods/" name="DOTM に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-tsv/" name="DOTM に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xltm/" name="DOTM に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xlt/" name="DOTM に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xlsm/" name="DOTM に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xlam/" name="DOTM に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-sxc/" name="DOTM に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/dotm-to-xlsb/" name="DOTM に XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}