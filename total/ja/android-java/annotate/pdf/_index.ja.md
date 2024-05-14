---
title: PDF 注釈をオンラインで削除するか、Android モバイル アプリを使用して注釈を管理する
description: オンライン アプリを使用して PDF ファイルからコメントを無料で削除します。PDF ファイルのコメントを管理するための Android API コード。

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="PDF ドキュメントからコメントをオンラインで消去するか、Android アプリで管理する" h2="強力な Android ベースの PDF ドキュメント注釈ユーティリティ アプリケーションを開発します。PDF ファイルのコメントを管理するためのコードをリストします。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF 注釈をオンラインで削除する" %}}

1. PDFファイルをインポートしてアップロードすることでコメントを削除します
1. 注釈アプリのドラッグアンドドロップでドロップエリア内をクリックして実行します
1. PDFファイルのサイズとインターネットの速度に応じて、数秒待ちます。
1. コメントを消去するには「削除」ボタンをクリックしてください
1. ファイルをすぐにダウンロード

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリ API 経由で PDF ドキュメントのコメントを削除する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. Documentクラスオブジェクト経由でドキュメントを読み込む
1. getPages().get_Item(Index)経由で特定のページを選択する
1. AnnotationSelectorを使用して、annotationSelector.getSelected()経由ですべてのテキスト注釈を取得します。
1. 各アノテーションを反復処理し、削除メソッドを呼び出して削除します。
1. ファイルを保存するには save メソッドを呼び出します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: PDF ファイルからコメントを削除する" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリ API 経由で注釈を追加する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. ドキュメントクラスオブジェクトを作成する
1. getPages().add() を使用して新しいページとコンテンツを追加します。
1. TextAnnotationクラスのgetPages().get_Item(Index)を使用する
1. タイトル、件名、内容などの関連する注釈を設定します
1. getAnnotations().addを使用して注釈を追加します
1. 保存メソッドを呼び出して、コメントを追加したファイルを保存します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: PDF注釈を追加" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PDF ドキュメント注釈 Android アプリの開発</h2>

フィードバックを提供したり、提案したり、ドキュメントについて他のユーザーと共同作業したりするための PDF 注釈モバイル アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for Android via Java](https://products.aspose.com/total/ja/android-java/) の子 API である [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/ja/android-java/) を使用すると、どの Android 開発者でも上記の API コードをドキュメント注釈アプリケーション内に統合できます。強力な Android ライブラリにより、あらゆるドキュメント注釈ソリューションをプログラミングできます。さらに、PDF 形式を含む多くの一般的な形式をサポートできます。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF ファイルに注釈を付ける Android ライブラリ" %}}

- 私たちは Java パッケージを [Maven リポジトリ](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/) でホストしています。 
- Aspose.PDF for Java はバイトコードを含む一般的な JAR ファイルです。
- Aspose.PDF for Android via Java のインストール方法については、[ステップバイステップの手順](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) に従ってください。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- Android API 31 および 32
- Android 4.0以上
- Android Studio と SDK ツール

<br />
JogAmp JOGL、Harfbuzz フォント エンジン、Java Advanced Imaging JAI などのオプション パッケージの依存関係の詳細については、[製品ドキュメント](https://docs.aspose.com/pdf/java/system-requirements/) を参照してください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}