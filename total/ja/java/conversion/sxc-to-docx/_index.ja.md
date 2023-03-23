---
title: Javaを使用してSXCをDOCXに変換する または無料のオンライン コンバーターを使用
description: ExcelまたはWordを使用してSXCをDOCXにエクスポートするJavaAPI またはオンライン またはオンライン。コードを統合する前に、無料の CSV から DOC へのオンライン コンバーターをすばやくテストします。
url_ignore: /ja/java/conversion/sxc-to-docx/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOCX
otherformats: PPTX WORD POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="SXCをDOCXにエクスポートするJavaAPI またはオンライン" h2="オンプレミスのJavaAPIを使用して、MicrosoftExcelに依存せずにSXCをDOCXにエクスポートします。" >}}
{{% blocks/products/pf/feature-page-summary %}}
SXCをDOCXにレンダリングするのは2段階のプロセスです。最初に[Aspose.CellsforJava](https://products.aspose.com/cells/java)APIを使用して特定のSXCドキュメントをPDFに変換し、次に[Aspose.Pdf for Java](https ：//products.aspose.com/pdf/java)APIを使用すると、PDFドキュメントをDOCXに簡単に変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)ファイル形式の自動化ライブラリのコレクションに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JavaAPIを介してSXCをDOCXに変換する方法" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してSXCファイルを開きます
2. SXCをPDFに変換し、SaveFormatをAUTOに設定します
3. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用して変換されたPDFファイルをロードします
4. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)を使用してドキュメントをDOCX形式で保存します-)メソッドとDocxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.TotalforJavaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>SXCからDOCXへのオンラインコンバーター</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=sxc" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/sxc-to-docx/">SXC から DOCX への変換用の無料アプリをお試しください</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}DOCX
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/sxc-to-docxx/" name="SXC に DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/sxc-to-pptx/" name="SXC に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/sxc-to-powerpoint/" name="SXC に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/sxc-to-word/" name="SXC に WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}