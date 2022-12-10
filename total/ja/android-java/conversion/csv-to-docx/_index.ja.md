---
title: AndroidのDOCXにCSVをエクスポートする
description: MicrosoftWordを使用せずにCSVをDOCXに変換するAndroidAPI

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOCX
otherformats: WORD DOC PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndroid上のDOCXにCSVをレンダリングする" h2="Microsoft <sup>＆reg; </ sup> Excelを使用せずに、Androidアプリケーション内でCSVをDOCXに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)は、強力なファイル自動化APIのパッケージです。 2つのAPIを使用することで、Androidアプリケーション内でCSVからDOCXへの変換機能を統合できます。最初のステップでは、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用してCSVをPDFにエクスポートできます。その後、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用して、PDFをDOCXに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CSVをDOCXにエクスポートするAndroidAPI" %}}
1. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してCSVファイルを開きます
2. CSVをPDFに変換し、SaveFormatをAUTOに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをDOCX形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/)と[Aspose.Cells for Android via Java](https://docxs.aspose.com/cells)をインストールしますアプリケーションの/java/ aspose-cells-for-android-via-java-installation /＃install-asposecells-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// save CSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのCSVファイルからカスタムプロパティを削除する" %}}Document
ドキュメントの変換とは別に、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)には、他にもたくさんの機能があります。変換プロセスの前に、CSVドキュメントのカスタムプロパティを削除できます。カスタムプロパティを削除するには、[DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String))メソッドを呼び出して、の名前を渡します。削除するドキュメントプロパティ。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
Documentve a list of all custom document properties of the Excel fileDocument
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-word/" name="CSV に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-docx/" name="CSV に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-pptx/" name="CSV に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-powerpoint/" name="CSV に POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}