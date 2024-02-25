---
title: DOCX 注釈をオンラインで削除するか、Java 経由で注釈を管理する
description: オンラインアプリを通じてDOCXファイルからコメントを無料で削除します。 DOCX ファイルのコメントを管理するための Java API コード。

family: total
platformtag: Java
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="オンラインで DOCX ドキュメントからコメントをクリアするか、Java 経由で管理する" h2="強力な Java ベースの DOCX ドキュメント注釈ユーティリティ アプリケーションを開発します。Java を介して DOCX ファイルのコメントを管理するためのコードのリスト。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCX 注釈をオンラインで削除する" %}}

1. DOCXファイルをインポートしてアップロードすることでコメントを削除します
1. 注釈アプリのドラッグ アンド ドロップでドロップ領域内をクリックして実行します。
1. DOCX ファイルのサイズとインターネット速度に応じて、数秒待ちます
1. コメントをクリアするには「削除」ボタンをクリックしてください
1. ファイルをすぐにダウンロードする

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java 経由で DOCX ドキュメントのコメントを削除する" %}}

1. Java プロジェクトにライブラリ参照を追加する
1. Document クラス オブジェクトを介してドキュメントをロードする
1. [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) と NodeType.COMMENT を使用して、すべてのノードからすべてのコメントを取得します。
1. [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) メソッドを呼び出してすべてのコメントを削除します
1. save メソッドを呼び出してファイルを保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="DOCX ファイルからコメントを削除する Java のコード例" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCX コメント返信の削除と追加" %}}

1. Java プロジェクトにライブラリ参照を追加する
1. Document クラス オブジェクトを介してドキュメントをロードする
1. getChildを使用してコメントを取得する
1. このコメントに対する指定された返信を削除するには [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) を使用してください
1. このコメントに返信を追加するには [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) を使用してください
1. save メソッドを呼び出してファイルを保存します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java 経由でコメントを追加する" %}}

1. Java プロジェクトにライブラリ参照を追加する
1. Documentクラスオブジェクトの作成
1. [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) を使用してコメントを作成します
1. getParagraphs().add および getFirstParagraph().getRuns().add を使用します。
1. save メソッドを呼び出してファイルを保存します with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="DOCX ファイルからコメント返信を削除および追加する Java コード" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java コード: コメントの追加" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Java による DOCX ドキュメント注釈アプリケーションの開発</h2>

ドキュメントに関してフィードバックを提供したり、提案を行ったり、他のユーザーと共同作業したりするために、DOCX 注釈アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for Java](https://products.aspose.com/total/java/) の子 API である [Aspose.Words for Java](https://products.aspose.com/words/java/) を使用すると、Java 開発者は上記の API コードをドキュメント注釈アプリケーション内に統合できます。強力な Java ライブラリにより、あらゆるドキュメント注釈ソリューションをプログラミングできます。さらに、DOCX 形式を含む多くの一般的な形式をサポートできます。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCX ファイルに注釈を付けるための Java ライブラリ" %}}
「[Aspose.Words for Java](https://products.aspose.com/words/java/)」または「[Aspose.Total for Java](https://products.aspose.com/total/java/)」をシステムにインストールするための代替オプションがあります。当社の Java パッケージはクロスプラットフォームになるように設計されており、Microsoft Windows、Linux、macOS、Android、iOS などのさまざまなオペレーティング システム上の JVM 実装と互換性があります。ニーズに近いものを選択し、ステップバイステップの指示に従ってください。<br />

- [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)をインストールする
- または[Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)から
- ステップバイステップ [説明書](https://docs.aspose.com/words/java/installation/#install-aspose-words-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- Java SE 7 または最新の Java バージョン
- この古い JRE をお持ちの場合は、Java SE 6 用の別個のパッケージが必要です。

<br />
JogAmp JOGL、Harfbuzz フォント エンジン、および Java Advanced Imaging JAI の詳細については、[製品ドキュメント](https://docs.aspose.com/words/java/system-requirements/#optional-dependencies) を参照してください。

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
                          <span itemprop="text">はい、このコードをダウンロードして、Java ベースのドキュメント注釈アプリケーションを開発する目的で使用してください。このコードは、バックエンドのドキュメント処理と操作の領域でプロジェクトの機能と機能を強化するための貴重なリソースとして機能します。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>このオンライン文書注釈アプリは Windows 上でのみ動作しますか?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows、Linux、Mac OS、Android など、実行されているオペレーティング システムに関係なく、任意のデバイスでコメント削除のためのドキュメント アノテーションを開始できる柔軟性があります。必要なのは、最新の Web ブラウザとアクティブなインターネット接続だけです。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>オンライン アプリを使用して DOCX ドキュメントに注釈を付けるのは安全ですか?</b></span>
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
                          <span itemprop="text">オンラインの DOCX ドキュメントの注釈には、Google Chrome、Firefox、Opera、Safari などの最新の Web ブラウザを使用できます。ただし、デスクトップ アプリケーションを開発している場合は、効率的な管理のために Aspose.Total ドキュメント処理 API を使用することをお勧めします。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}