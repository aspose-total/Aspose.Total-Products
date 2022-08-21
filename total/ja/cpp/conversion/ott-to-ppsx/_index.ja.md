---
title: C++を介してOTTをPPSXに変換する
description: Microsoft WordofPowerPointを使用せずにC++アプリケーションでOTTをPPSXにエクスポートする
url: /ja/cpp/conversion/ott-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: OTT
outformat: PPSX
otherformats: POTM ODP PPTX PPTM PPSM POTX PPT POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="OTTをPPSXに変換するC++API" h2="Microsoft Wordを使用せずに、C++アプリケーション内でOTTをPPSXにエクスポートします。またはPowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、2つのAPIを使用しながらOTTからPPSXへの変換を自動化できる強力なファイル自動化APIで構成されています。 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用してOTTを読み込み、HTMLに変換してから、PowerPoint操作C++ API [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/)を使用して新しいプレゼンテーションを作成し、PPSXとして保存します。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++でのOTTからPPSXへの変換" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)クラスリファレンスを使用してOTTファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_stdbasicostream_saveoptions)メンバー関数を使用してOTTをHTMLに変換します
3.新しい[プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)オブジェクトを初期化します
4.スライドにAutoShapeを追加し、それにAddTextFrameを追加します
5. HTMLコンテンツをロードし、プレゼンテーションファイルに書き込みます
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メソッドを使用してドキュメントをPPSX形式で保存し、PpsxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load OTT file with an instance of Ottument
Ottument ottument = new Ottument("template.ott");
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"sourceFile.ott");
// save the ottument in HTML file format
ott->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してパスワードで保護されたOTTドキュメントをロードする" %}}
ドキュメント変換とは別に、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用すると、C++開発者向けに多数のドキュメント操作機能を使用できます。 Microsoft Word OTTファイル形式がパスワードで保護されている場合でも、APIを使用して開くことができます。暗号化されたドキュメントをロードするために、[LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options)オブジェクトを受け入れる特別なコンストラクターオーバーロードを使用できます。このオブジェクトには、パスワード文字列を指定するPasswordプロパティが含まれています。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected ottument, the password is passed to the ottument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"ottPassword");
// load the ottument from the local file system by filename:
SharedPtr<Ottument> ott = MakeObject<Ottument>(u"Encrypted.ott", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してPPSXドキュメントにコメントを追加する" %}}
OTTをPPSXとして保存するときに、[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用してPPSXドキュメントに機能を追加することもできます。たとえば、プレゼンテーションにコメントを追加できます。プレゼンテーションスライドのコメントは、特定の作成者に関連付けられています。 Presentationクラスは、スライドコメントの追加を担当するICommentAuthorCollection内の作成者のコレクションを保持します。 ICommentCollectionには、作成者ごとにコメントのコレクションがあります。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-potm/" name="OTT に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-ppsx/" name="OTT に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-pptx/" name="OTT に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-pptm/" name="OTT に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-ppsm/" name="OTT に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-potx/" name="OTT に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-ppt/" name="OTT に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-powerpoint/" name="OTT に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-pot/" name="OTT に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/ott-to-pps/" name="OTT に PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}