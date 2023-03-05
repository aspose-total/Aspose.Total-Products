---
title: AndroidのPPTXにCSVをエクスポートする または無料のオンライン コンバーターを使用
description: MicrosoftWordを使用せずにCSVをPPTXに変換するAndroidAPI またはオンライン。コードを統合する前に、無料の CSV から DOC へのオンライン コンバーターをすばやくテストします。

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: PPTX
otherformats: POWERPOINT DOC WORD DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndroid上のPPTXにCSVをレンダリングする またはオンラインアプリ" h2="Microsoft <sup>＆reg; </ sup> Excelを使用せずに、Androidアプリケーション内でCSVをPPTXに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)は、強力なファイル自動化APIのパッケージです。 2つのAPIを使用することで、Androidアプリケーション内でCSVからPPTXへの変換機能を統合できます。最初のステップでは、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用してCSVをPDFにエクスポートできます。その後、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用して、PDFをPPTXに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CSVをPPTXにエクスポートするAndroidAPI" %}}
1. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してCSVファイルを開きます
2. CSVをPDFに変換し、SaveFormatをAUTOに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)クラスを使用して変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをPPTX形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/)と[Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells)をインストールしますアプリケーションの/java/ aspose-cells-for-android-via-java-installation /＃install-asposecells-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// save CSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>CSVからPPTXへの無料オンラインコンバーター</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=csv" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのCSVファイルからカスタムプロパティを削除する" %}}
ドキュメントの変換とは別に、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)には、他にもたくさんの機能があります。変換プロセスの前に、CSVドキュメントのカスタムプロパティを削除できます。カスタムプロパティを削除するには、[PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String))メソッドを呼び出して、の名前を渡します。削除するドキュメントプロパティ。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-powerpoint/" name="CSV に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-pptx/" name="CSV に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-word/" name="CSV に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/csv-to-pptxx/" name="CSV に PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}