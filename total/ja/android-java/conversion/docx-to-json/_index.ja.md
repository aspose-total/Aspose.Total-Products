---
title: Javaを介してAndroidでDOCXをJSON形式に変換する
description: Microsoft WordやExcelを使用せずに、Javaを介してAndroidでDOCXをJSON形式に解析します

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaを介してAndroidでDOCXをJSON形式に変換する" h2="Microsoft <sup>＆reg; </sup>WordまたはExcelを使用せずにDOCXをJSONにエクスポートするようにAndroidアプリケーションを設計する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用して、AndroidアプリケーションでDOCXをJSON形式に変換できます。ドキュメント操作および変換API[Aspose.Wordsfor Android via Java](https://products.aspose.com/words/android-java/)を使用すると、DOCXをHTMLにエクスポートできます。その後、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用して、HTMLをJSONに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでDOCXをJSON形式に変換する" %}}
1. [ドキュメント](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCXファイルを開きます
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してDOCXをHTMLに変換します) 方法
3. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをJSON形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。アプリにライブラリをインストールします。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="保護されたDOCXをJava経由でAndroidのJSON形式に変換する" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力DOCXドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。 APIを使用すると、LoadOptionsオブジェクトに正しいパスワードを渡すことで、暗号化されたドキュメントを開くことができます。次のコード例は、パスワードを使用して暗号化されたドキュメントを開く方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidの範囲内でDOCXをJSONに変換する" %}}
DOCXをJSONに変換しているときに、範囲を出力JSON形式に設定することもできます。範囲を設定するには、Workbookクラスを使用して変換されたHTMLを開き、Cells.createRangeメソッドを使用してエクスポートするデータの範囲を作成し、RangeとExportRangeToJsonOptionsを参照してJsonUtility.exportRangeToJsonメソッドを呼び出し、文字列JSONデータをファイルに書き込みます。 BufferedWriter.writeメソッド。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}