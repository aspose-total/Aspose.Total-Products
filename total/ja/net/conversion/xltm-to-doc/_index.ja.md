---
title: .NETを使用してXLTMをDOCに変換する 
description: .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでXLTMをDOCに変換する
url: /ja/net/conversion/xltm-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOC
otherformats: POWERPOINT DOCX PPTX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C＃経由でXLTMをDOCに変換" h2="Excelをエクスポート＆reg; .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでのXLTMからDOCへ">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NETでのXLTMからDOCへの変換" %}}
1. [ワークブック](https://apireference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLTMファイルを開きます
2. XLTMをPDFに変換し、SaveFormatをAutoに設定します
3. [ドキュメント](https://apireference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用して変換されたPDFファイルをロードします
4. [保存](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してドキュメントをDOC形式で保存し、DocをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="XLTMからDOCへの変換用の.NETC＃コード" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/csv-to-word/" name="CSV に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/csv-to-powerpoint/" name="CSV に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/csv-to-pptx/" name="CSV に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/csv-to-docx/" name="CSV に DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}