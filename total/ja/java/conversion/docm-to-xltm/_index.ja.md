---
title: DOCMをXLTMに変換するJavaAPI
description: MicrosoftWordやMicrosoftExcelを使用せずに、Java経由でDOCMをXLTMに変換する
url: /ja/java/conversion/docm-to-xltm/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: XLTM
otherformats: XLTX XLSM XLSX TSV XLT ODS XLSB SXC XLTM FODS DIF XLAM XLS EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でDOCMをXLTMに変換する" h2="オンプレミスのJavaAPIを使用して、Microsoft<sup>＆reg;</sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにDOCMをXLTMに変換する" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を介してDOCMをXLTMに変換するのは、単純な2ステップのプロセスです。機能豊富なドキュメント操作および変換API[Aspose.Wordsfor Java]（https://products.aspose.com/words/java/）を使用することにより、DOCMをHTMLにエクスポートできます。その後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、HTMLをXLTMに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCMをXLTMに変換するC++API" %}}
1. [ドキュメント]（https://apireference.aspose.com/words/java/com.aspose.words/Docmument）クラスを使用してDOCMファイルを開きます
2. [保存]（https://apireference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions）を使用してDOCMをHTMLに変換します） 方法
3. [Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用してHTMLドキュメントをロードします
4. [保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells）を使用して、ドキュメントをXLTM形式で保存します。 SaveOptions））メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できます[Aspose.Words for Java]（https://docms.aspose.com/words/java/installation/）と[Aspose.Cells for Java]（https://docms.aspose.com/cells/java/）を含めます。あなたのpom.xmlのinstallation/）。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
DOCMをXLTMに変換する前に、[Aspose.Words for Java]（https://products.aspose.com/words/java/）を介してDOCMドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions]（https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions）クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。ドキュメントから重複するスタイルや未使用のスタイルやリストを削除するには、[Cleanup]（https://apireference.aspose.com/words/java/com.aspose.words/Docmument#cleanup（））メソッドを使用できます。 [UnusedStyles]（https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles）と[UnusedBuiltinStyles]（https://apireference.aspose.com/words/java）を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles）「未使用」とマークされたスタイルを検出して削除するためのプロパティ。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してDOCMドキュメントから未使用の情報を削除する" %}}
DOCMをXLTMに変換した後、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用すると、ドキュメントをストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[保存]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io）する必要があります。 OutputStream、％20com.aspose.cells.SaveOptions））[Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlsm/" name="DOCM に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlt/" name="DOCM に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-ods/" name="DOCM に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-tsv/" name="DOCM に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xls/" name="DOCM に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlsb/" name="DOCM に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-fods/" name="DOCM に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-dif/" name="DOCM に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xltx/" name="DOCM に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlam/" name="DOCM に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xlsx/" name="DOCM に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-xltm/" name="DOCM に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-sxc/" name="DOCM に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/docm-to-excel/" name="DOCM に EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}