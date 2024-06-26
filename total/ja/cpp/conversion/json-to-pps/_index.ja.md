---
title: C++を介してJSON形式をPPSに変換する
description: MicrosoftPowerPointを使用せずにC++でJSONをPPSに解析する

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPSX PPSM PPTM POWERPOINT POTM POTX PPT ODP OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++を介してJSON形式をPPSに変換する" h2="Microsoft <sup>&reg;</sup>PowerPointを使用せずにJSONをPPSに解析するC++API" >}}

{{% blocks/products/pf/feature-page-summary %}}
2つの簡単なステップで、任意のC++アプリケーション内でJSONをPPSに変換できます。まず、[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)を使用して、JSONをPPTXに解析できます。その後、[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用して、PPTXをPPSに変換できます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++を介してJSON形式をPPSに変換する" %}}
1. しい[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)オブジェクトを作成し、ファイルから有効なJSONデータを読み取ります
2. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)メソッドを使用してJSONをPPTXとして保存します
3. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスを使用してPPTXドキュメントを読み込みます
4. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メソッドを使用してドキュメントをPPS形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="レイアウトを設定し、C++を介してJSON形式をPPSに変換します" %}}
JSONをPPSに解析するときに、[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラスを使用してJSONをロードすることにより、行と列のサイズを設定することもできます。ワークシートのすべての行に同じ行の高さを設定する必要がある場合は、[SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467fを使用して設定できます。 )[ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell)コレクションのメソッド。同様に、ワークシートのすべての列に同じ列幅を設定するには、ICellsコレクションの[SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7)メソッドを使用します。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++で透かしを使用してJSON形式をPPSに変換する" %}}
APIを使用して、JSONを透かし付きのPPSに変換することもできます。 PPSドキュメントに透かしを追加するには、最初にJSONをPPTXに解析して、透かしを追加します。透かしを追加するには、[プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスを使用して、新しく作成したPPTXファイルを読み込み、最初のスライドを取得して、 RectangleタイプのAutoShape、RectangleへのTextFrameの追加、テキストフレームのParagraphオブジェクトの作成、paragraphのPortionオブジェクトの作成、set_Text（)を使用した透かしの追加、およびドキュメントをPPSに保存できます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}