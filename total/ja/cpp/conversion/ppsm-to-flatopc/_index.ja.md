---
title: PPSMをFLATOPCに変換するC++API
description: C++アプリケーション内でPPSMをFLATOPCにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: FLATOPC
otherformats: RTF TEXT WORD DOTM DOCX DOCM DOC DOTX DOT OTT ODT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPSMをFLATOPCにレンダリングするC++API" h2="MicrosoftPowerPointやWordに依存せずにC++アプリケーションでPPSMをFLATOPCにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、C++ファイル形式自動化ライブラリの完全なパッケージです。 pacakgeで利用可能なAPIの豊富な機能を使用することで、PowerPointPPSMをWordFLATOPCに簡単に変換できます。変換を実行するには、最初に[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)APIを使用してPPSMをHTMLに変換できます。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、HTMLをFLATOPCに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSMをFLATOPCに変換するC++API" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPPSMファイルをロードします
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してPPSMをHTMLにレンダリングし、HtmlをSaveFormatとして設定します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument)クラスリファレンスを使用して、変換されたHTMLファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_string)メンバー機能を使用して、ドキュメントをFLATOPC形式で保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Flatopcument
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"htmlOutput.html");
// save flatopcument in FLATOPC format
flatopc->Save(u"output.flatopc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-rtf/" name="PPSM に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-text/" name="PPSM に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-word/" name="PPSM に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-dotm/" name="PPSM に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-flatopcx/" name="PPSM に FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-flatopcm/" name="PPSM に FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-flatopc/" name="PPSM に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-dotx/" name="PPSM に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-dot/" name="PPSM に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-ott/" name="PPSM に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-odt/" name="PPSM に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-wordml/" name="PPSM に WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}