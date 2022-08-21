---
title: C++でXLSBをPPTXに変換する
description: C++アプリケーション内でXLSBをPPTXに変換する
url: /ja/cpp/conversion/xlsb-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: DOCX WORD POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++経由でXLSBをPPTXに変換する" h2="Excelをエクスポート＆reg;フル機能のC++アプリケーション内でのXLSBからPPTXへ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++でのXLSBからPPTXへの変換" %}}
1. [Factory](https://reference.aspose.com/cells)の[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)メンバー関数を使用してXLSBファイルを開きます。 /cpp/class/aspose.cells.factory)クラスリファレンス
2. XLSBをPDFに変換し、SaveFormatをPdfに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)クラスリファレンスを使用して、変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db)メンバー関数を使用してドキュメントをPPTX形式で保存し、PptxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsb");
// save XLSB as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsb-to-pptxx/" name="XLSB に PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsb-to-word/" name="XLSB に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsb-to-powerpoint/" name="XLSB に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsb-to-pptx/" name="XLSB に PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}