---
title: オンラインで MHTML から MARKDOWN への変換、または MHTML ファイルを変換する Java ベースのアプリケーションの開発
description: MHTML を MARKDOWN ファイルに変換する無料オンライン アプリ。MHTML ドキュメント用の Java 変換ライブラリ コード。 

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: MARKDOWN
otherformats: RTF WORDML FLATOPC DOT ODT OTT DOTX DOTM PCL XAMLFLOW MARKDOWN PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="MHTML から MARKDOWN へのオンライン変換アプリと MHTML ファイルを変換する Java コード" h2="強力な Java ベースの MHTML 変換およびエクスポート アプリケーションを開発します。 Java 自動化 API を使用して、単一または複数の MHTML ファイルを MARKDOWN およびその他の形式に変換します。 アプリ経由で即座にダウンロードして、MHTML ファイルをオンラインで自由に変換します。" >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="無料のオンライン MHTML から MARKDOWN への変換アプリ" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=markdown&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="アプリを使用してオンラインでMHTMLをMARKDOWNファイルに変換する" %}}

1. 変換するMHTMLファイルをアップロードします
1. MHTMLのサイズに応じて数秒以上待ちます
1. アップロードステータスバーに注意してください
1. 「変換」ボタンをクリックします
1. MHTML は MARKDOWN ドキュメントに変換されます
1. 変換されたMARKDOWNファイルをダウンロードする

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Java Automation API 経由で MHTML を MARKDOWN に変換する" %}}


1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してMHTMLファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してMHTMLをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをMARKDOWN形式で保存し、MARKDOWNを設定しますSaveFormatとして



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "89f68c1b3e3c772c46b1f2adbaf240e5" "convert-mhtml-to-markdown.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

変換要件, Javaを介してパスワードで保護されたMHTMLドキュメントを開く などの他の機能を使用して MHTML を MARKDOWN に保存するケースがさらにいくつかあります。

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Java を使用して MHTML ファイル変換アプリケーションを開発する</h2>

MHTML ファイルを MARKDOWN ドキュメントに簡単に保存およびエクスポートするための Java ベースのソフトウェア アプリケーションを開発する必要がありますか? [Aspose.Total for Java](https://products.aspose.com/total/ja/java/) を使用すると、Java 開発者は誰でも上記の API コードを統合して、Microsoft Word (DOC、DOCX)、Excel (XLS、XLSX)、Powerpoint (PPT、PPTX)、PDF、電子メール ファイル、画像 (JPG、PNG、BMP、GIF) などのさまざまな形式にわたる変換アプリケーションをプログラムできます。 ドキュメント変換用の強力な Java ライブラリ。MHTML 形式を含む多くの一般的な形式をサポートしています。 ドキュメントを他の形式にエクスポートおよびレンダリングする場合、プログラマーは [Aspose.Words for Java](https://products.aspose.com/words/ja/java/)、[Aspose.Cells for Java](https://products.aspose.com/cells/ja/java/)、[Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/)、[Aspose.PDF for Java](https://products.aspose.com/pdf/ja/java/)、[Aspose.Imaging for Java](https://products.aspose.com/imaging/ja/java/) などの Aspose.Total for Java 子 API を使用できます。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Java 用変換ライブラリ" %}}

Aspose.Total for Java をシステムに統合するための代替オプションがあります。 ニーズに似たものを選択し、ステップバイステップの指示に従ってください。<br /><br />

- Maven ベースのプロジェクトから Aspose.Total for Java を直接使用し、関連する子 API を pom.xml に含めます。
- あるいは、[ダウンロード](https://releases.aspose.com/total/java) から ZIP ファイルを取得することもできます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="MHTML を MARKDOWN に保存するアプリの要件" %}}

Java Runtime Environment (JRE) を実行できるオペレーティング システムであれば、Aspose.Total for Java を実行できます。 以下に、サポートされているオペレーティング システムのほとんど (すべてではありません) をリストします。 <br /><br />
- マイクロソフトウィンドウズ
- Linux: Ubuntu、OpenSUSE、CentOS など
- macOS : 10.9 (Mavericks) 以降
- モバイル: Android、iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



MHTML（Webアーカイブ）ファイルをMARKDOWN（.md）に変換すると、Webコンテンツを軽量で読みやすく、ウェブサイト、ブログ、開発者向けドキュメントに適したポータブルなテキストに変換できます。Markdownは見出し、リンク、リスト、コードスニペットなどのコンテンツ構造を保持します。



{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}



* 開発者向けドキュメント用にWebチュートリアルをMarkdownに変換する。

* WebページからブログコンテンツをMarkdown形式でアーカイブする。

* オンラインマニュアルからナレッジベース記事を作成する。

* WebベースのレポートをポータブルなMarkdownノートに変換する。



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}



* 複数のMHTMLページをMarkdownに一括変換して静的サイトジェネレータに使用する。

* 開発者向けWikiの自動コンテンツ更新のためのトリガー付きMarkdown生成。

* CI/CDパイプラインと統合してWebコンテンツをドキュメントに変換する。

* Markdownベースのナレッジベース用にWebベースのレポートを自動抽出する。



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}