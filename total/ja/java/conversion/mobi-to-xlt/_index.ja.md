---
title: MOBIをXLTに変換するJavaAPI
description: MicrosoftWordやMicrosoftExcelを使用せずに、Java経由でMOBIをXLTに変換する
url: /ja/java/conversion/mobi-to-xlt/
family: total
platformtag: net
feature: conversion
informat: MOBI
outformat: XLT
otherformats: XLSM XLAM XLSX XLTX XLTM TSV FODS XLSB SXC ODS XLT DIF XLS EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でMOBIをXLTに変換する" h2="オンプレミスのJavaAPIを使用して、Microsoft<sup>＆reg;</sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにMOBIをXLTに変換する" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を介してMOBIをXLTに変換するのは、単純な2ステップのプロセスです。機能豊富なドキュメント操作および変換API[Aspose.Wordsfor Java]（https://products.aspose.com/words/java/）を使用することにより、MOBIをHTMLにエクスポートできます。その後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、HTMLをXLTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MOBIをXLTに変換するC++API" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Mobiument）クラスを使用してMOBIファイルを開きます
2. [保存]（https://apireference.aspose.com/words/java/com.aspose.words/Mobiument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してMOBIをHTMLに変換します） 方法
3. [Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用してHTMLドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells）を使用して、ドキュメントをXLT形式で保存します。 SaveOptions））メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できます[Aspose.Words for Java]（https://mobis.aspose.com/words/java/installation/）と[Aspose.Cells for Java]（https://mobis.aspose.com/cells/java/）を含めます。あなたのpom.xmlのinstallation/）。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
MOBIをXLTに変換する前に、[Aspose.Words for Java]（https://products.aspose.com/words/java/）を介してMOBIドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions]（https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions）クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。ドキュメントから重複するスタイルや未使用のスタイルやリストを削除するには、[Cleanup]（https://apireference.aspose.com/words/java/com.aspose.words/Mobiument#cleanup（））メソッドを使用できます。 [UnusedStyles]（https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles）と[UnusedBuiltinStyles]（https://apireference.aspose.com/words/java）を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles）「未使用」とマークされたスタイルを検出して削除するためのプロパティ。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-mobiument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してMOBIドキュメントから未使用の情報を削除する" %}}
MOBIをXLTに変換した後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用すると、ドキュメントをストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io）する必要があります。 OutputStream、％20com.aspose.cells.SaveOptions））[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xlsm/" name="MOBI に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xlt/" name="MOBI に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-ods/" name="MOBI に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-tsv/" name="MOBI に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xls/" name="MOBI に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xlsb/" name="MOBI に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-fods/" name="MOBI に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-dif/" name="MOBI に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xltx/" name="MOBI に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xlam/" name="MOBI に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xlsx/" name="MOBI に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-xltm/" name="MOBI に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-sxc/" name="MOBI に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/mobi-to-excel/" name="MOBI に EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}