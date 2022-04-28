---
title: DOTをODSに変換するJavaAPI
description: MicrosoftWordやMicrosoftExcelを使用せずに、Java経由でDOTをODSに変換する
url: /ja/java/conversion/dot-to-ods/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: ODS
otherformats: EXCEL XLT SXC XLTM XLS XLSB XLAM ODS DIF FODS XLSX XLTX XLSM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でDOTをODSに変換する" h2="オンプレミスのJavaAPIを使用して、Microsoft<sup>＆reg;</sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにDOTをODSに変換する" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を介してDOTをODSに変換するのは、単純な2ステップのプロセスです。機能豊富なドキュメント操作および変換API[Aspose.Wordsfor Java]（https://products.aspose.com/words/java/）を使用することにより、DOTをHTMLにエクスポートできます。その後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、HTMLをODSに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTをODSに変換するC++API" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Dotument）クラスを使用してDOTファイルを開きます
2. [保存]（https://apireference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してDOTをHTMLに変換します） 方法
3. [Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用してHTMLドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells）を使用して、ドキュメントをODS形式で保存します。 SaveOptions））メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できます[Aspose.Words for Java]（https://dots.aspose.com/words/java/installation/）と[Aspose.Cells for Java]（https://dots.aspose.com/cells/java/installation/）を含めますあなたのpom.xmlの。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
DOTをODSに変換する前に、[Aspose.Words for Java]（https://products.aspose.com/words/java/）を介してDOTドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions]（https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions）クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。ドキュメントから重複するスタイルや未使用のスタイルやリストを削除するには、[Cleanup]（https://apireference.aspose.com/words/java/com.aspose.words/Dotument#cleanup（））メソッドを使用できます。 [UnusedStyles]（https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles）と[UnusedBuiltinStyles]（https://apireference.aspose.com/words/java）を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles）「未使用」とマークされたスタイルを検出して削除するためのプロパティ。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してDOTドキュメントから未使用の情報を削除する" %}}
DOTをODSに変換した後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用すると、ドキュメントをストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook）[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xlsm/" name="DOT に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xlt/" name="DOT に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-ods/" name="DOT に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-tsv/" name="DOT に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xls/" name="DOT に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xlsb/" name="DOT に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-fods/" name="DOT に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-dif/" name="DOT に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xltx/" name="DOT に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xlam/" name="DOT に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xlsx/" name="DOT に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-xltm/" name="DOT に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-sxc/" name="DOT に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/dot-to-excel/" name="DOT に EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}