---
title: ODTをTSVに変換するAndroidAPI
description: MicrosoftWordまたはMicrosoftExcelを使用せずに、Javaを介してAndroidでODTをTSVに変換する
url: /ja/android-java/conversion/odt-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: TSV
otherformats: XLTM SXC XLSX DIF XLAM ODS EXCEL XLSB FODS CSV XLTX XLSM XLT XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndroidアプリケーションでODTをTSVに変換する" h2="Microsoft <sup>＆reg; </ sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにJava経由でAndroidのTSVにODTをエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でODTからTSVへの変換機能を統合できます。まず、機能豊富なドキュメント操作および変換API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、ODTをHTMLに変換できます。その後、[Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)を使用して、HTMLをTSVに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODTをTSVに変換するAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/words/java/com.aspose.words/Odtument)クラスを使用してODTファイルを開きます
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,com.aspose.words.SaveOptions)を使用してODTをHTMLに変換します) 方法
3. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをTSV形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Cells for Android via Java](https://odts.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository)および[Aspose.Words for Android via Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-アプリケーションのasposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのODTドキュメントから未使用の情報を削除する" %}}
ODTをTSVに変換する前に、[Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用してODTドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions)クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。重複するスタイル、または未使用のスタイルやリストのみをドキュメントから削除するには、[Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Odtument#cleanup（))メソッドを使用できます。 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles)と[UnusedBuiltinStyles](https://reference.aspose.com/words/java)を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)プロパティを使用して、「未使用」としてマークされているスタイルを検出して削除します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-odtument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="TSVファイルをJava経由でAndroidのストリームに保存" %}}
ODTをTSVに変換した後、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用すると、ドキュメントを保存してストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream、％20com.aspose.cells.SaveOptions))[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xltm/" name="ODT に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-sxc/" name="ODT に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xlsx/" name="ODT に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-dif/" name="ODT に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xlam/" name="ODT に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-ods/" name="ODT に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-excel/" name="ODT に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xlsb/" name="ODT に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-fods/" name="ODT に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-tsv/" name="ODT に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xltx/" name="ODT に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xlsm/" name="ODT に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xlt/" name="ODT に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/odt-to-xls/" name="ODT に XLS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}