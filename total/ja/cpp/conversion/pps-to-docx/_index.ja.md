---
title: PPSをDOCXに変換するC++API または無料のオンライン コンバーターを使用
description: C++アプリケーション内でPPSをDOCXにエクスポートする またはオンライン。コードを統合する前に、無料の PPS から DOCX へのオンライン コンバーターをすばやくテストします。

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCX
otherformats: WORDML TEXT ODT RTF DOTX DOT DOC FLATOPC DOCM WORD DOTM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PPSをDOCXにレンダリングするC++API またはオンラインアプリ" h2="MicrosoftPowerPointやWordに依存せずにC++アプリケーションでPPSをDOCXにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)は、C++ファイル形式自動化ライブラリの完全なパッケージです。 pacakgeで利用可能なAPIの豊富な機能を使用することで、PowerPointPPSをWordDOCXに簡単に変換できます。変換を実行するには、最初に[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)APIを使用してPPSをHTMLに変換できます。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、HTMLをDOCXに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSをDOCXに変換するC++API" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPPSファイルをロードします
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してPPSをHTMLにレンダリングし、HtmlをSaveFormatとして設定します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用して、変換されたHTMLファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)メンバー機能を使用して、ドキュメントをDOCX形式で保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOCX format
docx->Save(u"output.docx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>PPSからDOCXへの無料オンラインコンバーター</h3>

<iframe title="ppsからdocxへの変換オンラインツール" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=docx&from=pps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
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
                          <span itemprop="name"><b>オンラインで PPS を DOCX に変換するにはどうすればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">PPS変換用のオンラインアプリは上記に統合されています。このオンライン ツールを使用して PPS ファイルを DOCX に変換するには、PPS ファイルを指定された領域にドラッグ アンド ドロップするか、白い領域内をクリックしてデバイスからファイルを選択します。 PPS ファイルを選択したら、[変換] ボタンをクリックします。 PPS から DOCX への変換が完了したら、ワンクリックで変換された DOCX ファイルをダウンロードできます。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>PPS の変換にはどのくらいの時間がかかりますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">このオンライン コンバーターを使用した PPS から DOCX への変換の速度は、PPS ファイルのサイズに大きく依存します。小さい PPS ファイルは、わずか数秒で DOCX に変換できます。さらに、C++ アプリケーション内に変換コードを統合した場合、変換の速度は、変換プロセス用にアプリケーションをどの程度最適化したかによって異なります。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>無料の Aspose.Total コンバーターを使用して PPS を DOCX に変換しても安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろん！変換プロセスの後、DOCX ファイルのダウンロード リンクがすぐに利用できるようになります。プライバシーを確保するために、アップロードされたファイルは 24 時間後に削除され、この期間が過ぎるとダウンロード リンクは機能しなくなります。 PPS 変換を含むファイル変換は完全に安全でプライベートですのでご安心ください。無料アプリは主にテスト目的で統合されているため、コードを統合する前に結果を確認できます。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>PPS を変換するには、どのブラウザを使用すればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">オンラインの PPS から DOCX へのコンバーターは、Google Chrome、Firefox、Opera、Safari など、最新の Web ブラウザーと互換性があります。ただし、デスクトップ アプリケーションで作業している場合は、C++ アプリケーションとのシームレスな統合のために特別に設計された Aspose.Total PPS Conversion API の使用を検討することをお勧めします。この API は、アプリケーションのパフォーマンスを向上させる高速変換と高度な機能を提供します。さらに、幅広いファイル形式をサポートしているため、あらゆる変換ニーズに対応する多目的なソリューションとなっています。オンライン コンバーターと API のどちらを使用する場合でも、変換プロセス全体を通してファイルが安全に保護されていることを確認できます。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}