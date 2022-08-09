---
title: WORDをFODSに変換するAndroidAPI
description: MicrosoftWordまたはMicrosoftExcelを使用せずに、Javaを介してAndroidでWORDをFODSに変換する
url: /ja/android-java/conversion/word-to-fods/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: FODS
otherformats: XLTM TSV XLT XLSX EXCEL ODS XLS XLAM CSV XLTX XLSM XLSB DIF SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndroidアプリケーションでWORDをFODSに変換する" h2="Microsoft <sup>＆reg; </ sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにJava経由でAndroidのFODSにWORDをエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でWORDからFODSへの変換機能を統合できます。まず、機能豊富なドキュメント操作および変換API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、WORDをHTMLに変換できます。その後、[Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)を使用して、HTMLをFODSに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDをFODSに変換するAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/words/java/com.aspose.words/Wordument)クラスを使用してWORDファイルを開きます
2. [保存](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions)を使用してWORDをHTMLに変換します) 方法
3. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [保存](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをFODS形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Cells for Android via Java](https://words.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository)および[Aspose.Words for Android via Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-アプリケーションのasposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのWORDドキュメントから未使用の情報を削除する" %}}
WORDをFODSに変換する前に、[Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用してWORDドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions)クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。重複するスタイル、または未使用のスタイルやリストのみをドキュメントから削除するには、[Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Wordument#cleanup（))メソッドを使用できます。 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles)と[UnusedBuiltinStyles](https://reference.aspose.com/words/java)を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)プロパティを使用して、「未使用」としてマークされているスタイルを検出して削除します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-wordument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="FODSファイルをJava経由でAndroidのストリームに保存" %}}
WORDをFODSに変換した後、[Java経由のAndroid用Aspose.Cells](https://products.aspose.com/cells/android-java/)を使用すると、ドキュメントを保存してストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[保存](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream、％20com.aspose.cells.SaveOptions))[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xltm/" name="WORD に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-tsv/" name="WORD に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xlt/" name="WORD に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xlsx/" name="WORD に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-excel/" name="WORD に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-ods/" name="WORD に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xls/" name="WORD に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xlam/" name="WORD に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-fods/" name="WORD に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xltx/" name="WORD に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xlsm/" name="WORD に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-xlsb/" name="WORD に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-dif/" name="WORD に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/word-to-sxc/" name="WORD に SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}