---
title: OTTをXLSXに変換するJavaAPI
description: MicrosoftWordやMicrosoftExcelを使用せずに、Java経由でOTTをXLSXに変換する
url: /ja/java/conversion/ott-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLSX
otherformats: EXCEL XLT DIF XLSM XLTM FODS ODS XLSB XLTX XLSX XLAM SXC XLS TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でOTTをXLSXに変換する" h2="オンプレミスのJavaAPIを使用して、Microsoft <sup>＆reg; </ sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにOTTをXLSXに変換する" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を介してOTTをXLSXに変換するのは、単純な2ステップのプロセスです。機能豊富なドキュメント操作および変換API[Aspose.Wordsfor Java]（https://products.aspose.com/words/java/）を使用することにより、OTTをHTMLにエクスポートできます。その後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、HTMLをXLSXに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OTTをXLSXに変換するC++API" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Ottument）クラスを使用してOTTファイルを開きます
2. [保存]（https://apireference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してOTTをHTMLに変換します） 方法
3. [Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用してHTMLドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells）を使用して、ドキュメントをXLSX形式で保存します。 SaveOptions））メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できます[Aspose.Words for Java]（https://otts.aspose.com/words/java/installation/）と[Aspose.Cells for Java]（https://otts.aspose.com/cells/java/）を含めます。あなたのpom.xmlのinstallation/）。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
OTTをXLSXに変換する前に、[Aspose.Words for Java]（https://products.aspose.com/words/java/）を介してOTTドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions]（https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions）クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。ドキュメントから重複するスタイルや未使用のスタイルやリストを削除するには、[Cleanup]（https://apireference.aspose.com/words/java/com.aspose.words/Ottument#cleanup（））メソッドを使用できます。 [UnusedStyles]（https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles）と[UnusedBuiltinStyles]（https://apireference.aspose.com/words/java）を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles）「未使用」とマークされたスタイルを検出して削除するためのプロパティ。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-ottument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してOTTドキュメントから未使用の情報を削除する" %}}
OTTをXLSXに変換した後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用すると、ドキュメントをストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io）する必要があります。 OutputStream、％20com.aspose.cells.SaveOptions））[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xlsm/" name="OTT に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xlt/" name="OTT に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-ods/" name="OTT に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-tsv/" name="OTT に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xls/" name="OTT に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xlsb/" name="OTT に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-fods/" name="OTT に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-dif/" name="OTT に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xltx/" name="OTT に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xlam/" name="OTT に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xlsx/" name="OTT に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-xltm/" name="OTT に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-sxc/" name="OTT に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ott-to-excel/" name="OTT に EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}