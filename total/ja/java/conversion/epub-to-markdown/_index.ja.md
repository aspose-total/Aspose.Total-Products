---
title: EPUBをMARKDOWNにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してEPUBをMARKDOWNに変換する
url_ignore: /ja/java/conversion/epub-to-markdown/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MARKDOWN
otherformats: MARKDOWN DOT PCL ODT FLATOPC WORDML XAMLFLOW DOTX RTF DOTM PS OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してEPUBをMARKDOWNに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにEPUBをMARKDOWNにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、EPUBをMARKDOWNに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してEPUBファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをMARKDOWNに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをMARKDOWNに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してEPUBファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してEPUBをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをMARKDOWN形式で保存し、MARKDOWNを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-markdown.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
EPUBをMARKDOWNに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してEPUBを開く必要があります。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してパスワードで保護されたEPUBドキュメントを開く" %}}
入力ドキュメントをMARKDOWNファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 MARKDOWNをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
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

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
EPUBをMarkdownに変換することは、デジタル出版物から**軽量で開発者向けのコンテンツファイル**を生成するために非常に価値があります。Markdownはシンプルさ、クロスプラットフォーム互換性、静的サイトジェネレーターや開発者ツールとのシームレスな統合を保証します。EPUBをMarkdownに変換することで、出版社、開発者、オープンソースコミュニティは電子書籍コンテンツをドキュメンテーション、ブログ、共同出版のために再利用することができます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用シナリオ" %}}
- **静的サイトの公開** – Markdownベースの電子書籍コンテンツでモダンなウェブサイトを強化します。
- **GitHubベースのドキュメンテーション** – Gitリポジトリ内でコンテンツを直接管理およびバージョン管理します。
- **オープンソース電子書籍の共有** – Markdownファイルで普遍的に読める形式で書籍を配布します。
- **技術ブログ** – 開発者向けのブログコンテンツに電子書籍の章を変換します。
- **開発者向けの公開ワークフロー** – 軽量でポータブルなコンテンツ管理を実現します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}
- **EPUBからMarkdownへのパイプライン** – スケーラブルな公開のために電子書籍からMarkdownへの変換を自動化します。
- **Gitベースのシステムへの自動公開** – GitHubやGitLabなどのリポジトリと電子書籍コンテンツを同期します。
- **静的ウェブサイトの生成** – MarkdownコンテンツをJekyll、Hugo、またはNext.jsにフィードしてWeb公開します。
- **エンタープライズドキュメンテーションの自動化** – Markdown出力でドキュメンテーションワークフローを標準化します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}