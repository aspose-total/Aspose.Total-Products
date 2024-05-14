---
title: DOTX 注釈をオンラインで削除するか、Android モバイル アプリを使用して注釈を管理する
description: オンライン アプリを使用して DOTX ファイルからコメントを無料で削除します。DOTX ファイルのコメントを管理するための Android API コード。

family: total
platformtag: Android
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="DOTX ドキュメントからコメントをオンラインで消去するか、Android アプリで管理する" h2="強力な Android ベースの DOTX ドキュメント注釈ユーティリティ アプリケーションを開発します。DOTX ファイルのコメントを管理するためのコードをリストします。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX 注釈をオンラインで削除する" %}}

1. DOTXファイルをインポートしてアップロードすることでコメントを削除します
1. 注釈アプリのドラッグアンドドロップでドロップエリア内をクリックして実行します
1. DOTXファイルのサイズとインターネットの速度に応じて、数秒待ちます。
1. コメントを消去するには「削除」ボタンをクリックしてください
1. ファイルをすぐにダウンロード

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリで DOTX ドキュメントのコメントを削除する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. Documentクラスオブジェクト経由でドキュメントを読み込む
1. [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes)とNodeType.COMMENTを使用して、すべてのノードからすべてのコメントを取得します。
1. すべてのコメントを削除するには[clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear)メソッドを呼び出します
1. ファイルを保存するには save メソッドを呼び出します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: DOTX ファイルからコメントを削除する" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTXコメントの削除と追加 返信" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. Documentクラスオブジェクト経由でドキュメントを読み込む
1. getChildを使用してコメントを取得する
1. このコメントへの指定された返信を削除するには [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) を使用します
1. このコメントに返信を追加するには[addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String)を使用してください
1. ファイルを保存するにはsaveメソッドを呼び出します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Androidアプリでコメントを追加する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. ドキュメントクラスオブジェクトを作成する
1. [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/)を使用してコメントを作成する
1. getParagraphs().add と getFirstParagraph().getRuns().add を使用します。
1. ファイルを保存するにはsaveメソッドを呼び出します with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: DOTX ファイルからコメント返信を削除して追加する" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="コード: コメントの追加" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>DOTX ドキュメント注釈 Android アプリの開発</h2>

フィードバックを提供したり、提案したり、ドキュメントについて他のユーザーと共同作業したりするための DOTX 注釈モバイル アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for Android via Java](https://products.aspose.com/total/ja/android-java/) の子 API である [Aspose.Words for Android via Java](https://products.aspose.com/words/ja/android-java/) を使用すると、どの Android 開発者でも上記の API コードをドキュメント注釈アプリケーション内に統合できます。強力な Android ライブラリにより、あらゆるドキュメント注釈ソリューションをプログラミングできます。さらに、DOTX 形式を含む多くの一般的な形式をサポートできます。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX ファイルに注釈を付ける Android ライブラリ" %}}

- 私たちは Java パッケージを [Maven リポジトリ](https://releases.aspose.com/java/repo/com/aspose/aspose-words/) でホストしています。 
- Aspose.Words for Java はバイトコードを含む一般的な JAR ファイルです。
- Aspose.Words for Android via Java のインストール方法については、[ステップバイステップの手順](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) に従ってください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- Java SE 7 以降の Java バージョンがサポートされています。
- 古い JRE を使用する必要がある場合に備えて、Java SE 6 用の個別のパッケージを用意しました。
- Java パッケージはクロスプラットフォームであり、JVM 実装を備えたすべてのオペレーティング システムで実行されます。
- オペレーティング システムには、Microsoft Windows、Linux、macOS、Android、iOS が含まれます。

<br />
JogAmp JOGL、Harfbuzz フォント エンジン、Java Advanced Imaging JAI などのオプション パッケージの依存関係の詳細については、[製品ドキュメント](https://docs.aspose.com/words/java/system-requirements/) を参照してください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}