---
title: WORDMLをODSに変換するAndroidAPI
description: MicrosoftWordまたはMicrosoftExcelを使用せずに、Javaを介してAndroidでWORDMLをODSに変換する
url: /ja/android-java/conversion/wordml-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: ODS
otherformats: XLAM EXCEL XLS DIF XLSX XLSM XLTM XLSB XLT TSV FODS XLTX SXC CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndroidアプリケーションでWORDMLをODSに変換する" h2="Microsoft <sup>＆reg; </ sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにJava経由でAndroidのODSにWORDMLをエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でWORDMLからODSへの変換機能を統合できます。まず、機能豊富なドキュメント操作および変換API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、WORDMLをHTMLに変換できます。その後、[Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)を使用して、HTMLをODSに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDMLをODSに変換するAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument)クラスを使用してWORDMLファイルを開きます
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument#save(java.lang.String,com.aspose.words.SaveOptions)を使用してWORDMLをHTMLに変換します) 方法
3. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをODS形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Cells for Android via Java](https://wordmls.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository)および[Aspose.Words for Android via Java](https://wordmls.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-アプリケーションのasposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのWORDMLドキュメントから未使用の情報を削除する" %}}
WORDMLをODSに変換する前に、[Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用してWORDMLドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions)クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。重複するスタイル、または未使用のスタイルやリストのみをドキュメントから削除するには、[Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument#cleanup（))メソッドを使用できます。 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles)と[UnusedBuiltinStyles](https://reference.aspose.com/words/java)を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)プロパティを使用して、「未使用」としてマークされているスタイルを検出して削除します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-wordmlument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ODSファイルをJava経由でAndroidのストリームに保存" %}}
WORDMLをODSに変換した後、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用すると、ドキュメントを保存してストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream、％20com.aspose.cells.SaveOptions))[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xlam/" name="WORDML に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-excel/" name="WORDML に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xls/" name="WORDML に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-dif/" name="WORDML に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xlsx/" name="WORDML に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xlsm/" name="WORDML に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xltm/" name="WORDML に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xlsb/" name="WORDML に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xlt/" name="WORDML に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-tsv/" name="WORDML に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-fods/" name="WORDML に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-xltx/" name="WORDML に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-sxc/" name="WORDML に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/wordml-to-ods/" name="WORDML に ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}