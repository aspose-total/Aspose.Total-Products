---
title: EPUBをXLAMに変換するC++API
description: MicrosoftExcelまたはAdobeReaderを使用せずに、C++APIを介してEPUBをXLAMに変換します
url: /ja/cpp/conversion/epub-to-xlam/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: XLAM
otherformats: TSV EXCEL XLTX MD TXT FODS ODS XLSB CSV DIF SXC XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++アプリケーションでEPUBをXLAMにレンダリングする" h2="Microsoft <sup>&reg;</sup>ExcelまたはAdobe<sup>&reg;</sup> Acrobat Readerを必要とせずに、ネイティブC++アプリケーションでEPUBをXLAMに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)ファイル形式の自動化ライブラリを介してEPUBをC++でXLAMに変換するのは、単純な2ステップのプロセスです。最初のステップでは、[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用してEPUBをXLSXにエクスポートできます。その後、[Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/)スプレッドシートプログラミングAPI、XLSXをXLAMに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをXLAMに変換するC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してEPUBファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)メンバー関数を使用してEPUBをXLSXに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してXLSXドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)メンバー関数を使用してドキュメントをXLAM形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してEPUBファイル情報を取得または設定する" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用すると、EPUBドキュメントに関する情報を取得したり、変換プロセスの前に十分な情報に基づいて決定を下したりすることもできます。 EPUBファイルのファイル固有の情報を取得するには、最初に[get_Info（)](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a)メソッドを呼び出す必要があります。 [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラス。 DocumentInfoオブジェクトが取得されると、個々のプロパティの値を取得できます。さらに、DocumentInfoクラスのそれぞれのメソッドを使用してプロパティを設定することもできます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLAMファイル形式をC++経由でストリームに保存" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/)を使用すると、XLAMファイル形式をストリーミングに保存できます。ファイルをストリームに保存するには、MemoryStreamまたはFileStreamオブジェクトを作成し、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を呼び出してファイルをそのストリームオブジェクトに保存します。オブジェクトの[Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349)メソッド。 Saveメソッドを呼び出すときに、[SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a)列挙を使用して目的のファイル形式を指定します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlam-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-tsv/" name="EPUB に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-excel/" name="EPUB に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-xltx/" name="EPUB に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-md/" name="EPUB に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-txt/" name="EPUB に TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-fods/" name="EPUB に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-ods/" name="EPUB に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-xlsb/" name="EPUB に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-xlam/" name="EPUB に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-dif/" name="EPUB に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-sxc/" name="EPUB に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/epub-to-xlsm/" name="EPUB に XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}