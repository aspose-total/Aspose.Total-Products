---
title: DOCMをODSに変換するAndroidAPI
description: MicrosoftWordまたはMicrosoftExcelを使用せずに、Javaを介してAndroidでDOCMをODSに変換する

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: ODS
otherformats: SXC CSV XLTX XLAM XLS FODS DIF XLT XLSM TSV EXCEL XLSB XLTM XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="AndroidアプリケーションでDOCMをODSに変換する" h2="Microsoft <sup>＆reg; </ sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにJava経由でAndroidのODSにDOCMをエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、Androidアプリケーション内でDOCMからODSへの変換機能を統合できます。まず、機能豊富なドキュメント操作および変換API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、DOCMをHTMLに変換できます。その後、[Aspose.Cells for Java](https://products.aspose.com/cells/android-java/)を使用して、HTMLをODSに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCMをODSに変換するAndroidAPI" %}}
1. [ドキュメント](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCMファイルを開きます
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してDOCMをHTMLに変換します) 方法
3. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをODS形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.Cells for Android via Java](https://docms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository)および[Aspose.Words for Android via Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-アプリケーションのasposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのDOCMドキュメントから未使用の情報を削除する" %}}
DOCMをODSに変換する前に、[Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用してDOCMドキュメントから未使用の情報を削除できます。出力ドキュメントのサイズと処理時間を短縮するために、未使用または重複する情報を削除する必要がある場合があります。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions)クラスを使用すると、ドキュメントのクリーニングのオプションを指定できます。重複するスタイル、または未使用のスタイルやリストのみをドキュメントから削除するには、[Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup（))メソッドを使用できます。 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles)と[UnusedBuiltinStyles](https://reference.aspose.com/words/java)を使用できます/com.aspose.words/cleanupoptions#UnusedBuiltinStyles)プロパティを使用して、「未使用」としてマークされているスタイルを検出して削除します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ODSファイルをJava経由でAndroidのストリームに保存" %}}
DOCMをODSに変換した後、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用すると、ドキュメントを保存してストリームに保存できます。ファイルをストリームに保存する必要がある場合は、FileOutputStreamオブジェクトを作成してから、[Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream、％20com.aspose.cells.SaveOptions))[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)のsaveメソッドを呼び出して、そのStreamオブジェクトへのファイル物体。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-sxc/" name="DOCM に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-ods/" name="DOCM に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xltx/" name="DOCM に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xlam/" name="DOCM に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xls/" name="DOCM に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-fods/" name="DOCM に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-dif/" name="DOCM に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xlt/" name="DOCM に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xlsm/" name="DOCM に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-tsv/" name="DOCM に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-excel/" name="DOCM に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xlsb/" name="DOCM に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xltm/" name="DOCM に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/docm-to-xlsx/" name="DOCM に XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}