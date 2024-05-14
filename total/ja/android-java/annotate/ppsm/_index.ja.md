---
title: PPSM 注釈をオンラインで削除するか、Android モバイル アプリを使用して注釈を管理する
description: オンライン アプリを使用して PPSM ファイルからコメントを無料で削除します。PPSM ファイルのコメントを管理するための Android API コード。

family: total
platformtag: Android
feature: Annotate
informat: PPSM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="PPSMプレゼンテーションからオンラインでコメントをクリアするか、Androidアプリで管理する" h2="強力な Android ベースの PPSM プレゼンテーション注釈ユーティリティ アプリケーションを開発します。PPSM ファイルのコメントを管理するためのコードをリストします。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSM 注釈をオンラインで削除する" %}}

1. PPSMファイルをインポートしてアップロードすることでコメントを削除します
1. 注釈アプリのドラッグアンドドロップでドロップエリア内をクリックして実行します
1. PPSMファイルのサイズとインターネットの速度に応じて、数秒待ちます。
1. コメントを消去するには「削除」ボタンをクリックしてください
1. ファイルをすぐにダウンロード

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリで PPSM プレゼンテーションのコメントを削除する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. プレゼンテーションクラスオブジェクト経由でPPSMをロードする
1. Presentation.getCommentAuthors()コレクションを介して各著者を反復処理する
1. clear()メソッドを呼び出してコメントを削除します
1. 最後にgetCommentAuthors().clear()を呼び出してすべての著者を削除します
1. ファイルを保存するにはsaveメソッドを呼び出します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: PPSM プレゼンテーションからコメントと作成者を削除する" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリ経由で PPSM プレゼンテーション コメントを追加する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. プレゼンテーションクラスオブジェクト経由でPPSMをロードする
1. Presentation.getCommentAuthors().addAuthor(String, String)を呼び出して著者を追加する
1. コメントの追加にはICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)を使用する
1. ファイルを保存するにはsaveメソッドを呼び出します with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: コメントの追加" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PPSM ドキュメント注釈 Android アプリの開発</h2>

フィードバックを提供したり、提案したり、ドキュメントについて他のユーザーと共同作業したりするための PPSM 注釈モバイル アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for Android via Java](https://products.aspose.com/total/ja/android-java/) の子 API である [Aspose.Slides for Android via Java](https://products.aspose.com/slides/ja/android-java/) を使用すると、どの Android 開発者でも上記の API コードをドキュメント注釈アプリケーション内に統合できます。強力な Android ライブラリにより、あらゆるドキュメント注釈ソリューションをプログラミングできます。さらに、PPSM 形式を含む多くの一般的な形式をサポートできます。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSM ファイルに注釈を付ける Android ライブラリ" %}}

- 私たちは Java パッケージを [Maven リポジトリ](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/) でホストしています。 
- Aspose.Slides for Java はバイトコードを含む一般的な JAR ファイルです。
- Aspose.Slides for Android via Java のインストール方法については、[ステップバイステップの手順](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) に従ってください。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- J2SE 6.0 (Java 1.6) 以上
- Java パッケージはクロスプラットフォームであり、JVM 実装を備えたすべてのオペレーティング システムで実行されます。

<br />
詳細は[製品ドキュメント](https://docs.aspose.com/slides/java/system-requirements/)を参照してください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}