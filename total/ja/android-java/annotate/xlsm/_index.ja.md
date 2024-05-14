---
title: XLSM 注釈をオンラインで削除するか、Android モバイル アプリを使用して注釈を管理する
description: オンライン アプリを使用して XLSM ファイルからコメントを無料で削除します。XLSM ファイルのコメントを管理するための Android API コード。

family: total
platformtag: Android
feature: Annotate
informat: XLSM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="XLSM ドキュメントからコメントをオンラインで消去するか、Android アプリで管理する" h2="強力な Android ベースの XLSM ドキュメント注釈ユーティリティ アプリケーションを開発します。XLSM ファイルのコメントを管理するためのコードをリストします。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSM 注釈をオンラインで削除する" %}}

1. XLSMファイルをインポートしてアップロードすることでコメントを削除します
1. 注釈アプリのドラッグアンドドロップでドロップエリア内をクリックして実行します
1. XLSMファイルのサイズとインターネットの速度に応じて、数秒待ちます。
1. コメントを消去するには「削除」ボタンをクリックしてください
1. ファイルをすぐにダウンロード

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリ API 経由で XLSM ドキュメントのコメントを削除する" %}}

1. Android プロジェクトにライブラリ参照を追加する
1. Workbook クラス オブジェクト経由でドキュメントを読み込む
1. 特定のワークシートを選択
1. [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)を使用してすべてのコメントを取得する
1. すべてのスレッドコメントをgetThreadedComments経由で取得
1. コメントと著者を削除するにはそれぞれremoveAtを使用します
1. ファイルを保存するにはsaveメソッドを呼び出します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: XLSM ドキュメントからコメントを削除する" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="スレッド化された XLSM コメントを更新" %}}

1. Workbook クラス オブジェクト経由でドキュメントを読み込む
1. 特定のワークシートを入手する
1. getComments().getThreadedComments(Index).get(Index)を使用してスレッドコメントを取得する
1. コメントを更新するにはsetNotesメソッドを使用します
1. ファイルを保存するにはsaveメソッドを呼び出します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリ API 経由でコメントを追加する" %}}

1. Workbook クラス オブジェクトを使用してドキュメントを作成する
1. 特定のワークシートを入手する
1. getComments().add経由でコメントインデックスを追加
1. setNotesメソッドを使用してコメントを追加します
1. ファイルを保存するにはsaveメソッドを呼び出します with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="コード: XLSM ファイルのスレッドコメントを更新" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="コード: コメントの追加" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>XLSM ドキュメント注釈 Android アプリの開発</h2>

フィードバックを提供したり、提案したり、ドキュメントについて他のユーザーと共同作業したりするために、Android ベースの XLSM 注釈アプリまたはユーティリティを開発する必要がありますか?[Aspose.Total for Android via Java](https://products.aspose.com/total/ja/android-java/) の子 API である [Aspose.Cells for Android via Java](https://products.aspose.com/cells/ja/android-java/) を使用すると、どの Android 開発者でも上記の API コードをドキュメント注釈アプリケーション内に統合できます。強力な Android ライブラリにより、あらゆるドキュメント注釈ソリューションをプログラミングできます。さらに、XLSM 形式を含む多くの一般的な形式をサポートできます。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSM ファイルに注釈を付ける Android API" %}}

- 私たちは Java パッケージを [Maven リポジトリ](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/) でホストしています。 
- Aspose.Cells for Java はバイトコードを含む一般的な JAR ファイルです。
- Aspose.Cells for Android via Java のインストール方法については、[ステップバイステップの手順](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) に従ってください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

- Android OS 2.0以上。
- Java パッケージはクロスプラットフォームであり、JVM 実装を備えたすべてのオペレーティング システムで実行されます。

<br />
詳細は[製品ドキュメント](https://docs.aspose.com/cells/java/system-requirements/)を参照してください。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}