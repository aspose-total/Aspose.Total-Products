---
title: TEXをXLTMに変換するC++API
description: MicrosoftExcelまたはAdobeReaderを使用せずに、C++APIを介してTEXをXLTMに変換します
url: /ja/cpp/conversion/tex-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XLTM
otherformats: MD EXCEL XLTX FODS TXT XLSM TSV DIF XLSB ODS SXC XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++アプリケーションでTEXをXLTMにレンダリングする" h2="Microsoft <sup>&reg;</sup>ExcelまたはAdobe<sup>&reg;</sup> Acrobat Readerを必要とせずに、ネイティブC++アプリケーションでTEXをXLTMに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)ファイル形式の自動化ライブラリを介してTEXをC++でXLTMに変換するのは、単純な2ステップのプロセスです。最初のステップでは、[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用してTEXをXLSXにエクスポートできます。その後、[Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/)スプレッドシートプログラミングAPI、XLSXをXLTMに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEXをXLTMに変換するC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してTEXファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)メンバー関数を使用してTEXをXLSXに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してXLSXドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)メンバー関数を使用してドキュメントをXLTM形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してTEXファイル情報を取得または設定する" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用すると、TEXドキュメントに関する情報を取得したり、変換プロセスの前に十分な情報に基づいて決定を下したりすることもできます。 TEXファイルのファイル固有の情報を取得するには、最初に[get_Info（)](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a)メソッドを呼び出す必要があります。 [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラス。 DocumentInfoオブジェクトが取得されると、個々のプロパティの値を取得できます。さらに、DocumentInfoクラスのそれぞれのメソッドを使用してプロパティを設定することもできます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLTMファイル形式をC++経由でストリームに保存" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/)を使用すると、XLTMファイル形式をストリーミングに保存できます。ファイルをストリームに保存するには、MemoryStreamまたはFileStreamオブジェクトを作成し、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を呼び出してファイルをそのストリームオブジェクトに保存します。オブジェクトの[Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349)メソッド。 Saveメソッドを呼び出すときに、[SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a)列挙を使用して目的のファイル形式を指定します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltm-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-md/" name="TEX に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-excel/" name="TEX に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-xltx/" name="TEX に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-fods/" name="TEX に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-txt/" name="TEX に TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-xlsm/" name="TEX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-tsv/" name="TEX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-dif/" name="TEX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-xlsb/" name="TEX に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-ods/" name="TEX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-sxc/" name="TEX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-xlt/" name="TEX に XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}