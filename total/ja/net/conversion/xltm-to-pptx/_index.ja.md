---
title: .NETを使用してXLTMをPPTXに変換する または無料のオンライン コンバーターを使用
description: .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでXLTMをPPTXに変換する またはオンライン。コードを統合する前に、無料の CSV から DOC へのオンライン コンバーターをすばやくテストします。

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOCX POWERPOINT WORD DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="C＃経由でXLTMをPPTXに変換 またはオンラインアプリ" h2="Excelをエクスポート＆reg; .NET Framework、.NET Core、Mono、またはXamarinプラットフォームでのXLTMからPPTXへ">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NETでのXLTMからPPTXへの変換" %}}
1. [ワークブック](https://apireference.aspose.com/cells/net/aspose.cells/workbook)クラスを使用してXLTMファイルを開きます
2. XLTMをPDFに変換し、SaveFormatをAutoに設定します
3. [ドキュメント](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)クラスを使用して変換されたPDFファイルをロードします
4. [保存](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5)メソッドを使用してドキュメントをPPTX形式で保存し、PptxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="XLTMからPPTXへの変換用の.NETC＃コード" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLTMからPPTXへの無料オンラインコンバーター</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xltm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}