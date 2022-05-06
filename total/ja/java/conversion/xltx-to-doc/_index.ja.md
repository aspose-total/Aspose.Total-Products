---
title: Javaを使用してXLTXをDOCに変換する
description: ExcelまたはWordを使用してXLTXをDOCにエクスポートするJavaAPI
url_ignore: /ja/java/conversion/xltx-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOC
otherformats: DOCX PPTX POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XLTXをDOCにエクスポートするJavaAPI" h2="オンプレミスのJavaAPIを使用して、MicrosoftExcelに依存せずにXLTXをDOCにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
XLTXをDOCにレンダリングするのは2段階のプロセスです。最初に[Aspose.CellsforJava](https://products.aspose.com/cells/java)APIを使用して特定のXLTXドキュメントをPDFに変換し、次に[Aspose.Pdf for Java](https ：//products.aspose.com/pdf/java)APIを使用すると、PDFドキュメントをDOCに簡単に変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)ファイル形式の自動化ライブラリのコレクションに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JavaAPIを介してXLTXをDOCに変換する方法" %}}
1. [ワークブック](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してXLTXファイルを開きます
2. XLTXをPDFに変換し、SaveFormatをAUTOに設定します
3. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して変換されたPDFファイルをロードします
4. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをDOC形式で保存します-)メソッドとDocをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)ベースのプロジェクトから直接Aspose.TotalforJavaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://downloads.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/xltx-to-docx/" name="XLTX に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/xltx-to-pptx/" name="XLTX に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/xltx-to-powerpoint/" name="XLTX に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/xltx-to-word/" name="XLTX に WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}