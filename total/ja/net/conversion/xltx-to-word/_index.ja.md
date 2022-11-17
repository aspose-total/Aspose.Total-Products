---
title: .NETを使用してXLTXをWORDに変換する 
description: .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでXLTXをWORDに変換する

family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOC
otherformats: PPTX POWERPOINT DOC DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C＃経由でXLTXをWORDに変換" h2="Excelをエクスポート＆reg; .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでのXLTXからWORDへ">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NETでのXLTXからWORDへの変換" %}}
1. [ワークブック](https://apireference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLTXファイルを開きます
2. XLTXをPDFに変換し、SaveFormatをAutoに設定します
3. [ドキュメント](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument)クラスを使用して変換されたPDFファイルをロードします
4. [保存](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5)メソッドを使用してドキュメントをWORD形式で保存し、WordをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="XLTXからWORDへの変換用の.NETC＃コード" gistPath="" %}}
```cs
// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
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