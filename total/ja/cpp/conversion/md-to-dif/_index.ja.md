---
title: MDをDIFに変換するC++API
description: MicrosoftExcelまたはAdobeReaderを使用せずに、C++APIを介してMDをDIFに変換します

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DIF
otherformats: TXT FODS XLTM XLT ODS XLAM CSV XLTX TSV XLSM EXCEL SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++アプリケーションでMDをDIFにレンダリングする" h2="Microsoft <sup>&reg;</sup>ExcelまたはAdobe<sup>&reg;</sup> Acrobat Readerを必要とせずに、ネイティブC++アプリケーションでMDをDIFに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)ファイル形式の自動化ライブラリを介してMDをC++でDIFに変換するのは、単純な2ステップのプロセスです。最初のステップでは、[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用してMDをXLSXにエクスポートできます。その後、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)スプレッドシートプログラミングAPI、XLSXをDIFに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをDIFに変換するC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)メンバー関数を使用してMDをXLSXに変換します
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスリファレンスを使用してXLSXドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)メンバー関数を使用してドキュメントをDIF形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してMDファイル情報を取得または設定する" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用すると、MDドキュメントに関する情報を取得したり、変換プロセスの前に十分な情報に基づいて決定を下したりすることもできます。 MDファイルのファイル固有の情報を取得するには、最初に[get_Info（)](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a)メソッドを呼び出す必要があります。 [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラス。 DocumentInfoオブジェクトが取得されると、個々のプロパティの値を取得できます。さらに、DocumentInfoクラスのそれぞれのメソッドを使用してプロパティを設定することもできます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="DIFファイル形式をC++経由でストリームに保存" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/)を使用すると、DIFファイル形式をストリーミングに保存できます。ファイルをストリームに保存するには、MemoryStreamまたはFileStreamオブジェクトを作成し、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を呼び出してファイルをそのストリームオブジェクトに保存します。オブジェクトの[Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349)メソッド。 Saveメソッドを呼び出すときに、[SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a)列挙を使用して目的のファイル形式を指定します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-dif-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-txt/" name="MD に TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-fods/" name="MD に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-xltm/" name="MD に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-xlt/" name="MD に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-ods/" name="MD に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-xlam/" name="MD に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-dif/" name="MD に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-xltx/" name="MD に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-tsv/" name="MD に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-xlsm/" name="MD に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-excel/" name="MD に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-sxc/" name="MD に SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}