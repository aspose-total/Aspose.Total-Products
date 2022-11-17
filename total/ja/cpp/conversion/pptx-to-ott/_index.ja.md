---
title: PPTXをOTTに変換するC++API
description: C++アプリケーション内でPPTXをOTTにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: OTT
otherformats: TEXT DOCX WORD WORDML DOC DOT DOCM DOTX ODT RTF FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPTXをOTTにレンダリングするC++API" h2="MicrosoftPowerPointやWordに依存せずにC++アプリケーションでPPTXをOTTにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、C++ファイル形式自動化ライブラリの完全なパッケージです。 pacakgeで利用可能なAPIの豊富な機能を使用することで、PowerPointPPTXをWordOTTに簡単に変換できます。変換を実行するには、最初に[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)APIを使用してPPTXをHTMLに変換できます。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、HTMLをOTTに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPTXをOTTに変換するC++API" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPPTXファイルをロードします
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してPPTXをHTMLにレンダリングし、HtmlをSaveFormatとして設定します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)クラスリファレンスを使用して、変換されたHTMLファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string)メンバー機能を使用して、ドキュメントをOTT形式で保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-text/" name="PPTX に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-ottx/" name="PPTX に OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-word/" name="PPTX に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-wordml/" name="PPTX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-ott/" name="PPTX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-dot/" name="PPTX に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-ottm/" name="PPTX に OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-dotx/" name="PPTX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-odt/" name="PPTX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-rtf/" name="PPTX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-flatopc/" name="PPTX に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pptx-to-dotm/" name="PPTX に DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}