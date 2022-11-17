---
title: C++を介してRTFをPPTMに変換する
description: Microsoft WordofPowerPointを使用せずにC++アプリケーションでRTFをPPTMにエクスポートする

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: PPTM
otherformats: PPTX POTX POTM PPS PPT PPSX PPSM POWERPOINT ODP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="RTFをPPTMに変換するC++API" h2="Microsoft Wordを使用せずに、C++アプリケーション内でRTFをPPTMにエクスポートします。またはPowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、2つのAPIを使用しながらRTFからPPTMへの変換を自動化できる強力なファイル自動化APIで構成されています。 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用してRTFを読み込み、HTMLに変換してから、PowerPoint操作C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用して新しいプレゼンテーションを作成し、PPTMとして保存します。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++でのRTFからPPTMへの変換" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)クラスリファレンスを使用してRTFファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_stdbasicostream_saveoptions)メンバー関数を使用してRTFをHTMLに変換します
3.新しい[プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)オブジェクトを初期化します
4.スライドにAutoShapeを追加し、それにAddTextFrameを追加します
5. HTMLコンテンツをロードし、プレゼンテーションファイルに書き込みます
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メソッドを使用してドキュメントをPPTM形式で保存し、PptmをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load RTF file with an instance of Rtfument
Rtfument rtfument = new Rtfument("template.rtf");
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"sourceFile.rtf");
// save the rtfument in HTML file format
rtf->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してパスワードで保護されたRTFドキュメントをロードする" %}}
ドキュメント変換とは別に、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用すると、C++開発者向けに多数のドキュメント操作機能を使用できます。 Microsoft Word RTFファイル形式がパスワードで保護されている場合でも、APIを使用して開くことができます。暗号化されたドキュメントをロードするために、[LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options)オブジェクトを受け入れる特別なコンストラクターオーバーロードを使用できます。このオブジェクトには、パスワード文字列を指定するPasswordプロパティが含まれています。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected rtfument, the password is passed to the rtfument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"rtfPassword");
// load the rtfument from the local file system by filename:
SharedPtr<Rtfument> rtf = MakeObject<Rtfument>(u"Encrypted.rtf", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してPPTMドキュメントにコメントを追加する" %}}
RTFをPPTMとして保存するときに、[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用してPPTMドキュメントに機能を追加することもできます。たとえば、プレゼンテーションにコメントを追加できます。プレゼンテーションスライドのコメントは、特定の作成者に関連付けられています。 Presentationクラスは、スライドコメントの追加を担当するICommentAuthorCollection内の作成者のコレクションを保持します。 ICommentCollectionには、作成者ごとにコメントのコレクションがあります。
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-pptx/" name="RTF に PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-potx/" name="RTF に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-potm/" name="RTF に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-pps/" name="RTF に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-ppt/" name="RTF に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-ppsx/" name="RTF に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-ppsm/" name="RTF に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-powerpoint/" name="RTF に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-pptm/" name="RTF に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/rtf-to-pot/" name="RTF に POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}