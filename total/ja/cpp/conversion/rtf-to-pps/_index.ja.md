---
title: C++を介してRTFをPPSに変換する または無料のオンライン コンバーターを使用
description: Microsoft WordofPowerPointを使用せずにC++アプリケーションでRTFをPPSにエクスポートする またはオンライン。コードを統合する前に、無料の RTF から PPS へのオンライン コンバーターをすばやくテストします。

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: PPS
otherformats: PPT PPSM POTM POTX ODP PPSX POT POWERPOINT PPTM PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="RTFをPPSに変換するC++API またはオンラインアプリ" h2="Microsoft Wordを使用せずに、C++アプリケーション内でRTFをPPSにエクスポートします。またはPowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、2つのAPIを使用しながらRTFからPPSへの変換を自動化できる強力なファイル自動化APIで構成されています。 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用してRTFを読み込み、HTMLに変換してから、PowerPoint操作C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用して新しいプレゼンテーションを作成し、PPSとして保存します。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++でのRTFからPPSへの変換" %}}
1. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)クラスリファレンスを使用してRTFファイルを開きます
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_stdbasicostream_saveoptions)メンバー関数を使用してRTFをHTMLに変換します
3. しい[プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)オブジェクトを初期化します
4.スライドにAutoShapeを追加し、それにAddTextFrameを追加します
5. HTMLコンテンツをロードし、プレゼンテーションファイルに書き込みます
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メソッドを使用してドキュメントをPPS形式で保存し、PpsをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>RTFからPPSへの無料オンラインコンバーター</h3>

<iframe title="rtfからppsへの変換オンラインツール" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pps&from=rtf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

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

{{% blocks/products/pf/feature-page-section  h2="C++を介してPPSドキュメントにコメントを追加する" %}}
RTFをPPSとして保存するときに、[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用してPPSドキュメントに機能を追加することもできます。たとえば、プレゼンテーションにコメントを追加できます。プレゼンテーションスライドのコメントは、特定の作成者に関連付けられています。 Presentationクラスは、スライドコメントの追加を担当するICommentAuthorCollection内の作成者のコレクションを保持します。 ICommentCollectionには、作成者ごとにコメントのコレクションがあります。
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>よくある質問</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>オンラインで RTF を PPS に変換するにはどうすればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">上記の RTF 変換用のオンライン アプリを見つけることができます。変換プロセスを開始するには、RTF ファイルをドラッグ アンド ドロップするか、白い領域内をクリックしてドキュメントをインポートして、RTF ファイルを追加します。ファイルを追加したら、「変換」ボタンをクリックするだけです。 RTF から PPS への変換が完了したら、変換されたファイルをワンクリックでダウンロードできます。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>RTF の変換にはどのくらいの時間がかかりますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">このオンライン コンバーターの速度は、変換する RTF ファイルのサイズに大きく依存します。小さな RTF ファイルは、わずか数秒で PPS に変換できます。 C++ アプリケーション内で変換コードを使用している場合、変換速度はアプリケーションの最適化の程度によって異なります。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>無料の Aspose.Total コンバーターを使用して RTF を PPS に変換しても安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろん！オンライン コンバーターを使用して RTF ファイルを PPS に変換すると、PPS ファイルのダウンロード リンクがすぐに利用できるようになります。アップロードされたファイルのセキュリティとプライバシーを重視し、変換プロセスが完了してから 24 時間後に削除します。誰もあなたのファイルにアクセスできませんのでご安心ください。 RTF 変換を含む変換プロセスは完全に安全です。コードを統合する前に結果を確認できるように、テスト目的で無料のアプリを提供しています。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>RTF を変換するには、どのブラウザを使用すればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">オンライン RTF 変換には、Google Chrome、Firefox、Opera、Safari などの最新のブラウザーを使用できます。ただし、デスクトップ アプリケーションを開発している場合は、スムーズなパフォーマンスのために Aspose.Total RTF Conversion API をお勧めします。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}