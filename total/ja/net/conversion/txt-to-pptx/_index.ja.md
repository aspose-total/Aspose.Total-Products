---
title: C＃.NETを介してTXTをPPTXに変換する または無料のオンライン コンバーターを使用
description: C＃を使用してWordドキュメントドキュメントをPowerPointpptxファイルに変換します。 ASP.NETまたは他の.NETアプリケーション内で複数のファイルを変換します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C＃を使用してTXTをPPTXに変換する またはオンライン" h2=".NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームでMicrosoftWordTXTからPowerPointPPTXへの変換アプリを構築します。" logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="C＃を使用してTXTをPPTXに変換する またはオンライン方法" %}}

WordドキュメントファイルからPowerPointpptxプレゼンテーションへのバッチ変換のプロセスを自動化するために、[Aspose.Words for .NET](https://products.aspose.com/words/net)と[Aspose.Slides for .NET](https://products.aspose.com/slides/net)API。前者は、MicrosoftWord文書を処理または操作するためのワードプロセッシングAPIです。一方、後者は、MicrosoftPowerPointスライドを作成または変更できるプレゼンテーション操作APIです。両方のAPIは、[Aspose.Total for .NET](https://products.aspose.com/total/net)パッケージの一部です。 Nugetから直接[ダウンロード](https://releases.aspose.com/)するか、パッケージマネージャーコンソールから次のコマンドを使用できます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C＃を介してTXTをPPTXに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Totalfor.NETの参照を追加します
1. [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)クラスを使用してTXTファイルをロードします
1. TXTドキュメントをHTMLに保存します
1. [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)オブジェクトを作成します
1. プレゼンテーション内の任意のスライド形状のテキストフレームにHTMLコンテンツをインポートします
1. [Aspose.Slides.Presentation.Save（ "output.pptx"、SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods)を使用してドキュメントを保存します/ 5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

-Microsoft Windows、または.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォームと互換性のあるOS。
-MicrosoftVisualStudioのような開発環境。
--Aspose.Words for .NET＆amp;プロジェクトで参照されている.NETDLLの場合はAspose.Slides、.NETDLLの場合はAspose.Total。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このコードサンプルは、C＃を使用してTXTをPPTXに変換する またはオンライン方法を示しています" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>TXTからPPTXへのオンラインコンバーター</h3>

<iframe title="txtからpptxへの変換オンラインツール" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=pptx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="TXTをPPTXに変換する無料アプリ" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="プログラムでTXTファイルをPPTXに変換する：ユースケース" %}}
テキストファイル（.txt）からパワーポイントプレゼンテーション（.pptx）への変換は、プレゼンテーションの完全な可能性を引き出すために必要です。この変換により、次のような利益点が実現されます。

**用途:**

* **ビジネスプレゼンテーション**: テキストファイルを活用して、interactiveプレゼンテーションを作成し、複雑な情報を清潔に伝え、観客を魅覚することができます。
* **研究と学術プレゼンテーション**: パワーポイントで研究データを視化し、発見を発表し、同僚や利害関係者との知識共有を行うことができます。
* **マーケティングとセールスプレゼンテーション**: テキストファイルを活用して説得力あるプレゼンテーションを作成し、製品やサービスの紹介を行い、取引を締結することができます。
* **トレーニングと教育材料**: パワーポイントでinteractiveチュートリアルを作成し、学生が複雑な概念を導かれ、実践的なトレーニングを提供することができます。
* **内部コミュニケーション**: テキストファイルを活用して会社全体への発表や会社ニュースの共有を行い、チームでの協働作業を促進することができます。

テキストファイルをパワーポイントプレゼンテーションに変換することで、以下のような機能を追加することができます:

* ビジュアルコンテンツに画像、チャート、グラフを組み込むことができるようになります。
* interactive要素としてハイパーリンク、アニメーション、トランジションを追加することができます。
* マルチメディアコンテンツである音声やビデオファイルを含むことができるようになります。
* 謎の形式でプレゼンテーションを共有することができるようになります（.pptxなど）。

最後に、テキストファイルからパワーポイントプレゼンテーションへの変換は、効果的なビジュアルコミュニケーションを作成するための重要な手段です。
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
                          <span itemprop="name"><b>オンラインで TXT を PPTX に変換するにはどうすればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">TXT変換用のオンラインアプリは上記に統合されています。このアプリを使用するには、指定された白い領域に TXT ファイルをドラッグ アンド ドロップするか、領域内をクリックしてドキュメントをインポートして、TXT ファイルを追加します。次に、変換ボタンを押して変換プロセスを開始します。 TXT から PPTX への変換が完了したら、ワンクリックで新しく変換されたファイルをダウンロードでき、PPTX ファイルの形式で利用できます。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>TXT の変換にはどのくらいの時間がかかりますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">このオンライン コンバーターは迅速に動作しますが、主に変換される TXT ファイルのサイズに依存します。小さな TXT ファイルの場合、PPTX への変換は数秒で完了します。ただし、.NET アプリケーション内に変換コードを統合した場合、変換速度は、アプリケーションが変換プロセスに対してどの程度最適化されているかによって異なります。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>無料の Aspose.Total コンバーターを使用して TXT を PPTX に変換しても安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろん！ TXT から PPTX への変換が完了すると、新しく変換された PPTX ファイルのダウンロード リンクがすぐに利用できるようになります。また、TXT ファイルを含むアップロードされたすべてのファイルは完全に安全であり、24 時間後にシステムから削除されるため、変換プロセスの安全性も保証されます。さらに、この期間が過ぎるとダウンロード リンクが機能しなくなり、ファイルのプライバシーと保護が確保されます。統合アプリは無料で使用でき、テスト目的で設計されているため、ユーザーはコードをプロジェクトに統合する前に結果を評価できます。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>TXT を変換するには、どのブラウザを使用すればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">オンラインの TXT から PPTX への変換には、Google Chrome、Firefox、Opera、Safari などの最新の Web ブラウザーを使用できます。ただし、デスクトップ アプリケーションを開発している場合は、スムーズで効率的な処理のために Aspose.Total TXT Conversion API をお勧めします。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}