---
title: POTをRTFに変換するC++API
description: C++アプリケーション内でPOTをRTFにエクスポートする
url: /ja/cpp/conversion/pot-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: RTF
otherformats: ODT DOCM DOTM FLATOPC WORDML WORD OTT DOTX DOCX TEXT DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="POTをRTFにレンダリングするC++API" h2="MicrosoftPowerPointやWordに依存せずにC++アプリケーションでPOTをRTFにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、C++ファイル形式自動化ライブラリの完全なパッケージです。 pacakgeで利用可能なAPIの豊富な機能を使用することで、PowerPointPOTをWordRTFに簡単に変換できます。変換を実行するには、最初に[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)APIを使用してPOTをHTMLに変換できます。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、HTMLをRTFに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTをRTFに変換するC++API" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPOTファイルをロードします
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してPOTをHTMLにレンダリングし、HtmlをSaveFormatとして設定します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)クラスリファレンスを使用して、変換されたHTMLファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string)メンバー機能を使用して、ドキュメントをRTF形式で保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pot");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-odt/" name="POT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-rtfm/" name="POT に RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-dotm/" name="POT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-flatopc/" name="POT に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-wordml/" name="POT に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-word/" name="POT に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-ott/" name="POT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-dotx/" name="POT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-rtfx/" name="POT に RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-text/" name="POT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-rtf/" name="POT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/pot-to-dot/" name="POT に DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}