---
title: .NETを使用してXLSMをPPTXに変換する 
description: .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでXLSMをPPTXに変換する
url: /ja/net/conversion/xlsm-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: DOC POWERPOINT DOCX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C＃経由でXLSMをPPTXに変換" h2="Excelをエクスポート＆reg; .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでのXLSMからPPTXへ">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NETでのXLSMからPPTXへの変換" %}}
1. [ワークブック](https://apireference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLSMファイルを開きます
2. XLSMをPDFに変換し、SaveFormatをAutoに設定します
3. [ドキュメント](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)クラスを使用して変換されたPDFファイルをロードします
4. [保存](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5)メソッドを使用してドキュメントをPPTX形式で保存し、PptxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="XLSMからPPTXへの変換用の.NETC＃コード" gistPath="" %}}
```cs
// load the XLSM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsm");
// save XLSM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
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