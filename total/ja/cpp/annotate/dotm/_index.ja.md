---
title: DOTM 注釈をオンラインで削除するか、C++ で注釈を管理する
description: オンライン アプリを使用して DOTM ファイルからコメントを無料で削除します。DOTM ファイルのコメントを管理するための C++ API コード。

family: total
platformtag: cpp
feature: Annotate
informat: DOTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="DOTM ドキュメントからコメントをオンラインでクリアするか、C++ で管理する" h2="強力な C++ ベースの DOTM ドキュメント注釈ユーティリティ アプリケーションを開発します。C++ を介して DOTM ファイルのコメントを管理するためのコードがリストされています。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM 注釈をオンラインで削除する" %}}

1. DOTMファイルをインポートしてアップロードすることでコメントを削除します
1. 注釈アプリのドラッグアンドドロップでドロップエリア内をクリックして実行します
1. DOTMファイルのサイズとインターネットの速度に応じて、数秒待ちます。
1. コメントを消去するには「削除」ボタンをクリックしてください
1. ファイルをすぐにダウンロード

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="C++ 経由で DOTM ドキュメントのコメントを削除する" %}}

1. C++ プロジェクトにライブラリ参照を追加する
1. DOTMファイルを読み込む
1. NodeType::Commentをパラメータとして持つGetChildNodesを使用してすべてのノードを取得します。
1. コメントコレクションでNodeCollection.Clearを呼び出す

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ コード: DOTM ファイルからコメントを削除する" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ でコメントを追加する" %}}

1. Document および DocumentBuilder クラス オブジェクトを作成する
1. またはドキュメントを読み込む
1. コメントを追加するにはCommentクラスを使用します
1. コメントobjをパラメータとしてAppendChildメソッドを使用する
1. get_Paragraphs()->Addのような関連メソッドを使用する
1. あるいは、CommentRangeStartクラスとCommentRangeEndクラスを使用する方法もあります。
1. 保存メソッドを呼び出して、コメントを追加したファイルを保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="すべてのコメントを抽出" %}}

1. Documentクラスオブジェクト経由でドキュメントを読み込む
1. NodeCollection 内のすべての GetChildNodes を取得します。
1. 各コレクションを反復処理して、それらに関する情報を収集します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ コード: DOTM ファイルにコメントを追加する" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: すべてのコメントを抽出" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>C++ による DOTM ドキュメント注釈アプリケーションの開発</h2>

フィードバックを提供したり、提案したり、ドキュメントについて他のユーザーと共同作業したりするための DOTM 注釈アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for C++](https://products.aspose.com/total/ja/cpp/) の子 API である [Aspose.Words for C++](https://products.aspose.com/words/cpp/) を使用すると、どの C++ 開発者でも上記の API コードをドキュメント注釈アプリケーション内に統合できます。強力な C++ ライブラリにより、あらゆるドキュメント注釈ソリューションをプログラミングできます。さらに、DOTM 形式を含む多くの一般的な形式をサポートできます。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM ファイルに注釈を付ける C++ ライブラリ" %}}

開発環境に Aspose.Words for C++ をインストールするには、3 つのオプションがあります。ニーズに似たものを選択し、ステップバイステップの指示に従ってください。<br /><br />

- Install a [NuGet パッケージ](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [ドキュメンテーション](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Visual Studio IDE内で[パッケージ マネージャー コンソール](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console)を使用してライブラリをインストールする
- [Windowsインストーラー](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)を使用して手動でライブラリをインストールする

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}
この C++ ライブラリを使用して、Microsoft Windows、Linux、macOS オペレーティング システム上でソフトウェアを開発できます。<br /><br />

- LinuxではGCC >= 6.3.0およびClang >= 3.9.1が必要です
- macOS には Xcode >= 12.5.1、Clang、libc++ が必要です

<br /><br />
Linux または macOS 用のソフトウェアを開発する場合は、[製品ドキュメント](https://docs.aspose.com/words/cpp/system-requirements/) で追加のライブラリ依存関係 (fontconfig および mesa-glu オープンソース パッケージ) に関する情報を確認してください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="よくある質問" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>よくある質問</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>上記の C++ コードをアプリケーションで使用できますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">はい、このコードをダウンロードして、C++ ベースのドキュメント注釈アプリケーションの開発に活用していただけます。このコードは、バックエンドのドキュメント処理と操作の領域でプロジェクトの機能と能力を強化するための貴重なリソースとして役立ちます。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>このオンライン ドキュメント注釈アプリは Windows でのみ動作しますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows、Linux、Mac OS、Android など、どのオペレーティング システムで実行されているかに関係なく、どのデバイスでもドキュメントの注釈を開始してコメントを削除できます。必要なのは、最新の Web ブラウザーとアクティブなインターネット接続だけです。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>オンライン アプリを使用して DOTM ドキュメントに注釈を付けるのは安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろんです! 当社のサービスを通じて生成された出力ファイルは、24 時間以内に当社サーバーから安全かつ自動的に削除されます。その結果、これらのファイルに関連付けられた表示リンクは、この期間を過ぎると機能しなくなります。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>アプリを使用するにはどのブラウザが必要ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">オンライン DOTM ドキュメント注釈には、Google Chrome、Firefox、Opera、Safari などの最新の Web ブラウザを使用できます。ただし、デスクトップ アプリケーションを開発している場合は、効率的な管理のために Aspose.Total ドキュメント処理 API を使用することをお勧めします。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}