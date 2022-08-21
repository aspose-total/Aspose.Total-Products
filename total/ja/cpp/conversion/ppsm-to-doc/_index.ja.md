---
title: PPSMをDOCに変換するC++API
description: C++アプリケーション内でPPSMをDOCにエクスポートする
url: /ja/cpp/conversion/ppsm-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOC
otherformats: FLATOPC DOTM DOCM WORD DOTX WORDML TEXT OTT DOT ODT RTF DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPSMをDOCにレンダリングするC++API" h2="MicrosoftPowerPointやWordに依存せずにC++アプリケーションでPPSMをDOCにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、C++ファイル形式自動化ライブラリの完全なパッケージです。 pacakgeで利用可能なAPIの豊富な機能を使用することで、PowerPointPPSMをWordDOCに簡単に変換できます。変換を実行するには、最初に[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)APIを使用してPPSMをHTMLに変換できます。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、HTMLをDOCに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSMをDOCに変換するC++API" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPPSMファイルをロードします
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してPPSMをHTMLにレンダリングし、HtmlをSaveFormatとして設定します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用して、変換されたHTMLファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)メンバー機能を使用して、ドキュメントをDOC形式で保存します。
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
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOC format
doc->Save(u"output.doc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-flatopc/" name="PPSM に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-dotm/" name="PPSM に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-docm/" name="PPSM に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-word/" name="PPSM に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-dotx/" name="PPSM に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-wordml/" name="PPSM に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-text/" name="PPSM に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-ott/" name="PPSM に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-dot/" name="PPSM に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-odt/" name="PPSM に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-rtf/" name="PPSM に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ppsm-to-docx/" name="PPSM に DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}