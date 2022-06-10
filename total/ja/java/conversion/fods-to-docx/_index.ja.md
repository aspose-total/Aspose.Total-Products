---
title: Javaを使用してFODSをDOCXに変換する
description: ExcelまたはWordを使用してFODSをDOCXにエクスポートするJavaAPI
url_ignore: /ja/java/conversion/fods-to-docx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOCXX
otherformats: POWERPOINT WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="FODSをDOCXにエクスポートするJavaAPI" h2="オンプレミスのJavaAPIを使用して、MicrosoftExcelに依存せずにFODSをDOCXにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
FODSをDOCXにレンダリングするのは2段階のプロセスです。最初に[Aspose.CellsforJava](https://products.aspose.com/cells/java)APIを使用して特定のFODSドキュメントをPDFに変換し、次に[Aspose.Pdf for Java](https ：//products.aspose.com/pdf/java)APIを使用すると、PDFドキュメントをDOCXに簡単に変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)ファイル形式の自動化ライブラリのコレクションに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JavaAPIを介してFODSをDOCXに変換する方法" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してFODSファイルを開きます
2. FODSをPDFに変換し、SaveFormatをAUTOに設定します
3. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して変換されたPDFファイルをロードします
4. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをDOCX形式で保存します-)メソッドとDocxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)ベースのプロジェクトから直接Aspose.TotalforJavaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://downloads.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/fods-to-docxx/" name="FODS に DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/fods-to-pptx/" name="FODS に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/fods-to-powerpoint/" name="FODS に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/fods-to-word/" name="FODS に WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}