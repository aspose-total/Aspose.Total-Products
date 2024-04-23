---
title: オンラインまたは Android モバイル アプリを使用して XLS ファイルにデジタル署名する
description: XLS スプレッドシートのデジタル署名用の無料オンライン アプリ。XLS スプレッドシートに電子署名する Android アプリケーションを開発します。

family: total
platformtag: Android
feature: Signature
informat: XLS
otherformats: PDF WORD DOC DOCX ODT POWERPOINT PPT PPTX ODP Excel XLS XLSX ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="オンラインまたはAndroidアプリを使用してXLSファイルにデジタル署名する" h2="強力な Android ベースの XLS ドキュメント署名アプリケーションを開発します。アプリをすぐにダウンロードして、XLS ファイルを含むさまざまなドキュメントにオンラインでデジタル署名を自由に追加できます。" >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="オンラインで XLS ファイルにデジタル署名を追加する" %}}

1. XLSファイルをアップロードしてデジタル署名する
1. 署名用のテキストを追加するか、署名画像をアップロードします
1. 「署名」ボタンをクリックします
1. 署名されたXLSファイルをダウンロードする

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android アプリ経由で XLS ファイルにデジタル署名する" %}}

1. プロジェクトにJavaライブラリ参照を追加する
1. DigitalSignatureCollectionクラスオブジェクトを作成する
1. FileInputStream経由でpfxをロードする
1. PKCS12暗号化を使用したKeyStoreオブジェクトの作成
1. 証明書ストリームとパスワードを読み込むにはKeyStore.loadメソッドを使用します。
1. DigitalSignatureのインスタンスを作成し、コレクションに追加する
1. Workbookを使用してワークシートをロードする
1. setDigitalSignature(signatures)を使用してワークシートに署名する
1. 最後に保存する

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Java コード: XLS ファイルにデジタル署名を追加する" offSpacer="" %}}

{{< gist "aspose-com-gists" "dfee7ff74de7a59021c6ebe710e99f9b" "add-digital-signature-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Android を使用した電子署名アプリケーションの開発</h2>

複数の XLS ファイルに簡単にデジタル署名するための Android スクリプトまたはユーティリティ アプリを開発する必要がありますか?[Aspose.Total for Android via Java](https://products.aspose.com/total/ja/android-java/) の子 API である [Aspose.Cells for Android via Java](https://products.aspose.com/cells/ja/android-java/) を使用すると、どの Android 開発者でも上記の API コードを統合して、スプレッドシート間で署名するための電子署名アプリをプログラムできます。スプレッドシート署名用の強力な Android ライブラリ。XLS 形式を含む多くの一般的な形式をサポートしています。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android アプリ向け XLS 電子署名ライブラリ" %}}

- 私たちは Java パッケージを [Maven リポジトリ](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/) でホストしています。 
- Aspose.Cells for Java はバイトコードを含む一般的な JAR ファイルです。
- Aspose.Cells for Android via Java のインストール方法については、[ステップバイステップの指示](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) に従ってください。

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