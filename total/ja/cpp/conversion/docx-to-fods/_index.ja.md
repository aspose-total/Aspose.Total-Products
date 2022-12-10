---
title: C++でDOCXをFODSに変換する
description: MicrosoftWordまたはMicrosoftExcelを使用せずにDOCXをFODSに変換するC++API

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: FODS
otherformats: XLSM XLTM SXC EXCEL CSV XLSB XLTX XLSX XLT DIF XLAM ODS TSV XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="DOCXをFODSに変換するC++API" h2="Microsoft <sup>&reg;</sup>WordまたはMicrosoft<sup>&reg;</sup>Excelを使用せずにC++経由でDOCXをFODSにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++アプリケーションにDOCXからFODSへの変換機能を簡単に含めることができます。機能豊富で強力で使いやすいドキュメント操作および変換API[Aspose.Wordsfor C++](https://products.aspose.com/words/cpp/)を使用することで、DOCXをHTMLにエクスポートできます。その後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用して、HTMLをFODSに変換できます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCXをFODSに変換するC++API" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用してDOCXファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メンバー関数を使用してDOCXをHTMLに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)メンバー関数を使用してドキュメントをFODS形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++経由でDOCXドキュメントのプロパティにアクセスする" %}}DocumentDocument
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)では、DOCXファイルのドキュメントプロパティにアクセスし、変換プロセスの前に十分な情報に基づいて決定を下すことができます。ドキュメントのプロパティにアクセスするには、[BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties)を使用して、組み込みのプロパティと[CustomDocxumentProperties](https：// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties)を使用して、カスタムプロパティを取得します。次のコード例は、ドキュメント内のすべての組み込みプロパティとカスタムプロパティを列挙する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="FODSファイルをC++経由でストリームに保存" %}}
DOCXをFODSに変換した後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用すると、ドキュメントをストリーミングに保存できます。ファイルをストリームに保存するには、MemoryStreamまたはFileStreamオブジェクトを作成し、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を呼び出してファイルをそのストリームオブジェクトに保存します。オブジェクトの[Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349)メソッド。 [Save](https://reference.aspose.com)を呼び出すときに、[SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a)列挙を使用して目的のファイル形式を指定します。メソッド。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xlsm/" name="DOCX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xltm/" name="DOCX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-sxc/" name="DOCX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-excel/" name="DOCX に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-fods/" name="DOCX に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xlsb/" name="DOCX に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xltx/" name="DOCX に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xlsx/" name="DOCX に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xlt/" name="DOCX に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-dif/" name="DOCX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xlam/" name="DOCX に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-ods/" name="DOCX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-tsv/" name="DOCX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/docx-to-xls/" name="DOCX に XLS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}