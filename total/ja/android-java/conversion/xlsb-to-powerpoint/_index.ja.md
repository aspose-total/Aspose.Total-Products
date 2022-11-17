---
title: AndroidのPOWERPOINTにXLSBをエクスポートする
description: MicrosoftWordを使用せずにXLSBをPOWERPOINTに変換するAndroidAPI

family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: PPTX WORD DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndroid上のPOWERPOINTにXLSBをレンダリングする" h2="Microsoft <sup>＆reg; </ sup> Excelを使用せずに、Androidアプリケーション内でXLSBをPOWERPOINTに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)は、強力なファイル自動化APIのパッケージです。 2つのAPIを使用することで、Androidアプリケーション内でXLSBからPOWERPOINTへの変換機能を統合できます。最初のステップでは、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用してXLSBをPDFにエクスポートできます。その後、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用して、PDFをPOWERPOINTに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSBをPOWERPOINTにエクスポートするAndroidAPI" %}}
1. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLSBファイルを開きます
2. XLSBをPDFに変換し、SaveFormatをAUTOに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)クラスを使用して変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをPOWERPOINT形式で保存します-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/)と[Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells)をインストールしますアプリケーションの/java/ aspose-cells-for-android-via-java-installation /＃install-asposecells-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://downloads.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのXLSBファイルからカスタムプロパティを削除する" %}}
ドキュメントの変換とは別に、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)には、他にもたくさんの機能があります。変換プロセスの前に、XLSBドキュメントのカスタムプロパティを削除できます。カスタムプロパティを削除するには、[PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String))メソッドを呼び出して、の名前を渡します。削除するドキュメントプロパティ。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xlsb-to-pptx/" name="XLSB に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xlsb-to-word/" name="XLSB に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xlsb-to-powerpoint/" name="XLSB に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/android-java/conversion/xlsb-to-powerpointx/" name="XLSB に POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}