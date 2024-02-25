---
title: DOCXをC++でJSON形式に変換する
description: MicrosoftExcelまたはWordを使用せずにC++でDOCXをJSONにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++を介してDOCXをJSON形式に変換する" h2="Microsoft <sup>&reg;</sup>WordまたはExcelを使用せずにC++経由でDOCXをJSONにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)を使用すると、C++アプリケーション内でDOCXをJSON形式に変換できます。まず、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、DOCXをHTMLにエクスポートできます。その後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用して、HTMLをJSON形式に変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++を介してDOCXをJSON形式に変換する" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用してDOCXファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メンバー関数を使用してDOCXをHTMLに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)メンバー関数を使用してドキュメントをJSON形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
```Install-PackageAspose.Total.Cpp```を使用してVisualStudioのパッケージマネージャーコンソールからインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたDOCXをC++経由でJSON形式に変換する" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力DOCXドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。これを行うには、LoadOptionsオブジェクトを受け入れる特別なコンストラクターオーバーロードを使用します。このオブジェクトには、パスワード文字列を指定するPasswordプロパティが含まれています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}