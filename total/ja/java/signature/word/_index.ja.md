---
title: オンラインまたは Java を使用して Word ファイルにデジタル署名する
description: Word ファイルにデジタル署名を行うための無料オンライン アプリ。Word ドキュメントに電子署名するための Java アプリケーションを開発します。

family: total
platformtag: Java
feature: Signature
informat: Word
otherformats: PDF WORD DOC DOCX ODT POWERPOINT PPT PPTX ODP IMAGE JPG JPEG BMP TIFF GIF PNG PSD Excel XLS XLSX ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="電子署名アプリまたは Java を使用してオンラインで Word ファイルにデジタル署名" h2="強力な Java ベースの Word 文書署名アプリケーションを開発します。瞬時にダウンロードできるアプリを介して、オンラインで Word ファイルを含むさまざまなドキュメントにデジタル署名を自由に追加できます。" >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="アプリを使用してオンラインで Word ファイルにデジタル署名を追加" %}}

1. Word ファイルをアップロードしてデジタル署名する
1. 署名用のテキストを追加するか、署名画像をアップロードします
1. 「署名」ボタンをクリックします
1. 署名された Word ファイルをダウンロードする

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java 経由で Word ファイルにデジタル署名する" %}}

1. Java ライブラリ参照をプロジェクトに追加する
1. Documentクラスオブジェクトの作成
1. ビルダークラス経由でオブジェクトをロードする
1. SignatureLineOptions オブジェクトを作成し、オプションを定義する
1. insertSignatureLine(signatureLineOptions).getSignatureLine() を使用して行オプションを挿入します。
1. Wordドキュメントを保存し、SignOptionsオブジェクトを作成します
1. CertificateHolder を使用して pfx ファイルをロードします
1. 関連するパラメータを指定して DigitalSignatureUtil.sign メソッドを使用して署名します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Word ファイルにデジタル署名を追加するための Java コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "dfee7ff74de7a59021c6ebe710e99f9b" "digitally-sign-word-documents.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Javaを使用した電子署名アプリケーションの開発</h2>

複数の Word ファイルに簡単にデジタル署名するための Java スクリプトまたはユーティリティ アプリを開発する必要がありますか?[Aspose.Total for Java](https://products.aspose.com/total/ja/java/) の子 API である [Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) を使用すると、Java 開発者は上記の API コードを統合して、複数のドキュメントに署名するための電子署名アプリをプログラムできます。ドキュメント署名用の強力な Java ライブラリは、Word 形式を含む多くの一般的な形式をサポートします。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java 用 Word 電子署名ライブラリ" %}}
「[Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/)」または「[Aspose.Total for Java](https://products.aspose.com/total/ja/java/)」をシステムにインストールするための代替オプションがあります。当社の Java パッケージはクロスプラットフォームになるように設計されており、Microsoft Windows、Linux、macOS、Android、iOS などのさまざまなオペレーティング システム上の JVM 実装と互換性があります。ニーズに近いものを選択し、ステップバイステップの指示に従ってください。<br />

- [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)をインストールする
- または[Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)から
- ステップバイステップ [説明書](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- Java SE 7 または最新の Java バージョン
- この古い JRE をお持ちの場合は、Java SE 6 用の別個のパッケージが必要です。

<br />
JogAmp JOGL、Harfbuzz フォント エンジン、および Java Advanced Imaging JAI の詳細については、[製品ドキュメント](https://docs.aspose.com/slides/java/system-requirements/#optional-dependencies) を参照してください。

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
                          <span itemprop="name"><b>上記の Java コードをアプリケーションで使用できますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">はい、このコードをダウンロードして構いません。Java を使用して、Word ファイルにデジタル署名を追加する専門的なソリューションを簡単に開発できます。Aspose Word eSignature API を使用して、Java でプラットフォームに依存しない高レベルのソフトウェアを開発します。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>この文書のデジタル署名アプリは Windows でのみ動作しますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows、Linux、Mac OS、Android など、実行されているオペレーティング システムに関係なく、任意のデバイスから文書署名を開始できる柔軟性があります。必要なのは、最新の Web ブラウザとアクティブなインターネット接続だけです。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>オンライン アプリを使用して複数の Word ドキュメントに署名するのは安全ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">もちろん！当社のサービスを通じて生成された出力ファイルは、24 時間以内に当社のサーバーから安全かつ自動的に削除されます。その結果、これらのファイルに関連付けられたダウンロード リンクは、この期間が過ぎると機能しなくなります。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>アプリを使用するにはどのブラウザが必要ですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">オンライン Word ドキュメント圧縮には、Google Chrome、Firefox、Opera、Safari などの最新の Web ブラウザを使用できます。</span>
                      </div>
                  </li>
 		  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>複数の Word ファイルに署名するにはどうすればよいですか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">まず、署名したい 1 つ以上のファイルをアップロードします。Word ファイルをドラッグ アンド ドロップするか、白い領域内をクリックするだけです。その後、「署名」ボタンをクリックすると、オンライン署名アプリがアップロードされたファイルを迅速に処理します。</span>
                      </div>
                  </li>
 		  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Word ファイルに署名するのにどれくらい時間がかかりますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">この電子署名アプリケーションは高速に動作します。ファイルをアップロードして署名するまでに数秒かかる場合があります。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}