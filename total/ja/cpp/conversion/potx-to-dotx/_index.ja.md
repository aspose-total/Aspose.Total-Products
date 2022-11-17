---
title: POTXをDOTXに変換するC++API
description: C++アプリケーション内でPOTXをDOTXにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOTX
otherformats: RTF DOT DOCX WORD WORDML FLATOPC DOCM OTT ODT TEXT DOC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="POTXをDOTXにレンダリングするC++API" h2="MicrosoftPowerPointやWordに依存せずにC++アプリケーションでPOTXをDOTXにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、C++ファイル形式自動化ライブラリの完全なパッケージです。 pacakgeで利用可能なAPIの豊富な機能を使用することで、PowerPointPOTXをWordDOTXに簡単に変換できます。変換を実行するには、最初に[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)APIを使用してPOTXをHTMLに変換できます。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、HTMLをDOTXに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTXをDOTXに変換するC++API" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPOTXファイルをロードします
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してPOTXをHTMLにレンダリングし、HtmlをSaveFormatとして設定します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)クラスリファレンスを使用して、変換されたHTMLファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string)メンバー機能を使用して、ドキュメントをDOTX形式で保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotxument
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"htmlOutput.html");
// save dotxument in DOTX format
dotx->Save(u"output.dotx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-rtf/" name="POTX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-dot/" name="POTX に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-dotxx/" name="POTX に DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-word/" name="POTX に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-wordml/" name="POTX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-flatopc/" name="POTX に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-dotxm/" name="POTX に DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-ott/" name="POTX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-odt/" name="POTX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-text/" name="POTX に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-dotx/" name="POTX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/potx-to-dotm/" name="POTX に DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}