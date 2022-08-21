---
title: C++でXLSXをPOWERPOINTに変換する
description: C++アプリケーション内でXLSXをPOWERPOINTに変換する
url: /ja/cpp/conversion/xlsx-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: PPTX DOCX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++経由でXLSXをPOWERPOINTに変換する" h2="Excelをエクスポート＆reg;フル機能のC++アプリケーション内でのXLSXからPOWERPOINTへ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++でのXLSXからPOWERPOINTへの変換" %}}
1. [Factory](https://reference.aspose.com/cells)の[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)メンバー関数を使用してXLSXファイルを開きます。 /cpp/class/aspose.cells.factory)クラスリファレンス
2. XLSXをPDFに変換し、SaveFormatをPdfに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)クラスリファレンスを使用して、変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db)メンバー関数を使用してドキュメントをPOWERPOINT形式で保存し、PowerpointをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");
// save XLSX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsx-to-pptx/" name="XLSX に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsx-to-powerpointx/" name="XLSX に POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsx-to-powerpoint/" name="XLSX に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xlsx-to-word/" name="XLSX に WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}