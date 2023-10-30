---
title: Python を使用してオンラインで RTF ファイルからテキストと画像を抽出する
description: オンラインRTFファイルパーサーアプリ。 RTF ドキュメントから画像とテキストを抽出する Python API コード。

family: total
platformtag: Python
feature: Parse
informat: RTF
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="RTF ファイルをオンラインで解析し、Python 経由でテキストや画像を抽出します" h2="強力な Python ベースの RTF ドキュメント パーサー ユーティリティ アプリケーションを開発します。RTF ドキュメント画像と Python によるテキスト抽出用のコードがリストされています。" >}}




{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="オンラインアプリ経由でRTFドキュメントを解析" %}}

1. 解析するRTFファイルをアップロードしてインポートします。
1. これを行うには、パーサー アプリのドラッグ アンド ドロップでドロップ領域内をクリックします。
1. RTF ファイルのサイズとインターネット速度に応じて、数秒待ちます。
1. 「今すぐ解析」ボタンをクリックしてドキュメントを解析します。
1. 解析されたファイルをダウンロードすると、すぐに表示されます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Python 経由で RTF ファイルからテキストを抽出する" %}}

1. PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) からプロジェクト内の API を直接参照する
1. テキスト抽出プロセスに含めるノードを定義する
1. 最初と最後のノードを含めるか除外する
1. 指定したノードのコンテンツを抽出する
1. 抽出されたテキスト用に別の RTF ドキュメントを作成する
1. extract_content 関数にリストされたコード.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="RTF ドキュメント テキストを抽出する Python のコード例" offSpacer="" %}}

{{< gist "aspose-com-gists" "5c38d534a5a47b6e6c0e62620a50c6b9" "extract-text-from-word-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Python 経由で RTF ファイルから画像を抽出する" %}}

1. PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) からプロジェクト内の API を直接参照する
1. Document オブジェクトの Shape ノードに保存された画像
1. すべての Shape ノードを選択するには、Document.get_child_nodes メソッドを使用します。
1. 結果として得られるノード コレクションをループします。
1. Shape.has_image が true を返す場合。
1. 画像データを抽出するには、Shape.image_data プロパティを使用します。
1. 画像データをファイルに保存する
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="RTF ドキュメント画像を抽出するための Python のコード例" offSpacer="" %}}

{{< gist "aspose-com-gists" "5c38d534a5a47b6e6c0e62620a50c6b9" "extract-images-from-word-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Python による RTF ファイル パーサー アプリケーションの開発</h2>

RTF パーサー アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) の子 API である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用すると、Python 開発者は上記の API コードをドキュメント パーサー アプリケーション内に統合できます。強力な Python ライブラリを使用すると、テキストだけでなく画像も抽出するドキュメント解析ソリューションをプログラミングできます。さらに、RTF 形式を含む多くの一般的な形式をサポートできます。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="パーサー アプリ用に RTF ファイルを処理する Python ユーティリティ" %}}
「[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)」または「[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/)」をシステムにインストールする別のオプションもあります。ニーズに近いものを選択し、ステップバイステップの指示に従ってください。<br /><br />

- [pypi](https://pypi.org/project/aspose-words/)から[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)をインストール
- または、次の pip コマンド ``pip install aspose.words`` を使用します。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- Python 3.5以降がインストールされていること
- GCC-6 ランタイム ライブラリ (またはそれ以降)。
- .NET Core ランタイムの依存関係。 .NET Core ランタイム自体をインストールする必要はありません。
- Python 3.5 ～ 3.7 の場合: Python の pymalloc ビルドが必要です。
<br /><br />
詳細については[製品ドキュメント](https://docs.aspose.com/words/python-net/system-requirements/)を参照してください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupRTFs.cloud/templates/brand/images/groupRTFs/conversion/groupRTFs_conversion-brand.png" alt="よくある質問" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>よくある質問</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>上記の Python コードをアプリケーションで使用できますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">はい、このコードをダウンロードして、Python ベースのドキュメント パーサー アプリケーションを開発する目的で利用しても構いません。このコードは、ノードの読み取りや、テキストや画像を抽出するためのドキュメントのロードなど、バックエンド ドキュメント処理のドメインでプロジェクトの機能と機能を強化するための貴重なリソースとして機能します。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>このオンライン ドキュメント パーサー アプリは Windows 上でのみ動作しますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows、Linux、Mac OS、Android など、実行されているオペレーティング システムに関係なく、任意のデバイスでドキュメントの解析を開始できる柔軟性があります。必要なのは、最新の Web ブラウザとアクティブなインターネット接続だけです。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>RTF ドキュメントの解析にオンライン アプリを使用しても安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろん！当社のサービスを通じて生成された出力ファイルは、24 時間以内に当社のサーバーから安全かつ自動的に削除されます。その結果、これらのファイルに関連付けられた表示リンクは、この期間を過ぎると機能しなくなります。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>アプリを使用するにはどのブラウザが必要ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">オンライン RTF ドキュメント パーサーには、Google Chrome、Firefox、Opera、Safari などの最新の Web ブラウザーを使用できます。ただし、デスクトップ アプリケーションを開発している場合は、効率的な管理のために Aspose.Total ドキュメント処理 API を使用することをお勧めします。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}