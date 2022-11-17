---
title: C++でODSをDOCに変換する
description: C++アプリケーション内でODSをDOCに変換する

family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: DOC
otherformats: POWERPOINT PPTX DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++経由でODSをDOCに変換する" h2="Excelをエクスポート＆reg;フル機能のC++アプリケーション内でのODSからDOCへ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++でのODSからDOCへの変換" %}}
1. [Factory](https://reference.aspose.com/cells)の[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)メンバー関数を使用してODSファイルを開きます。 /cpp/class/aspose.cells.factory)クラスリファレンス
2. ODSをPDFに変換し、SaveFormatをPdfに設定します
3. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用して、変換されたPDFファイルをロードします
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)メンバー関数を使用してドキュメントをDOC形式で保存し、DocをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ods-to-powerpoint/" name="ODS に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ods-to-pptx/" name="ODS に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ods-to-docx/" name="ODS に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ods-to-word/" name="ODS に WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}