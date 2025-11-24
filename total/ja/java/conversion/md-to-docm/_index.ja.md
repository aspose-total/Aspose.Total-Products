---
title: MDをDOCMにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してMDをDOCMに変換する
url_ignore: /ja/java/conversion/md-to-docm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOCM
otherformats: DOTM PS XAMLFLOW RTF MARKDOWN FLATOPC OTT PCL DOT WORDML ODT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してMDをDOCMに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにMDをDOCMにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、MDをDOCMに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してMDファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをDOCMに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをDOCMに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してMDファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してMDをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをDOCM形式で保存し、DOCMを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
MDをDOCMに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してMDを開く必要があります。  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してパスワードで保護されたMDドキュメントを開く" %}}
入力ドキュメントをDOCMファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 DOCMをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
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

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



MD（Markdown）ファイルをDOCX（Word Macro-Enabled Documents）に変換することで、チームは軽量なテキストファイルをインタラクティブな自動化機能で強化できます。 DOCMファイルは埋め込みマクロをサポートしており、ワークフロー駆動のドキュメント、企業テンプレート、Word内で動的なアクションが必要な自動生成レポートに最適です。



{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}



* 開発者のMarkdownノートをマクロパワーのSOPに変換する。

* 企業ワークフロー向けの自動アクション対応ポリシードキュメント。

* Gitに保存されたMDファイルから構築されたインタラクティブな提案テンプレート。

* Markdownベースの変更履歴から生成されたマクロ駆動の監査ログ。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}



* コンプライアンスチーム向けの定期的なMDからDOCMへの変換。

* Markdownからマクロ対応のWordレポートを生成するETLパイプライン。

* リポジトリコンテンツからDOCMドキュメントを再生成するCI/CDワークフロー。

* エンジニアリング部門向けの自動マクロトリガードドキュメンテーション。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}