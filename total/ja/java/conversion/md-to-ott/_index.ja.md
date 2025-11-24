---
title: MDをOTTにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してMDをOTTに変換する
url_ignore: /ja/java/conversion/md-to-ott/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: OTT
otherformats: DOT FLATOPC DOTX ODT XAMLFLOW PS WORDML PCL MHTML MARKDOWN DOTM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してMDをOTTに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにMDをOTTにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、MDをOTTに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してMDファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをOTTに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをOTTに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してMDファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してMDをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをOTT形式で保存し、OTTを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
MDをOTTに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してMDを開く必要があります。  
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
入力ドキュメントをOTTファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 OTTをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.OTT);
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



Markdown（MD）をOTT（OpenDocument Text Template）に変換すると、オープンソースオフィススイート向けのスケーラブルなテンプレート作成がサポートされます。OTTテンプレートは一貫した書式を維持しながら、安定したスタイルの基盤から複数のドキュメントを生成することができます。



{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}



* 多言語ドキュメント制作用のOTTテンプレートの作成。

* Markdownベースのガイドラインから構造化されたレポートテンプレートの構築。

* オープンソース環境向けのオフィス文書の標準化。

* NGOや公共機関向けの再利用可能なODTドキュメント形式の生成。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}



* オープンソースのパブリッシングワークフローでの自動化されたOTT生成。

* Markdownバージョン管理から同期されたテンプレートの更新の展開。

* LibreOfficeを使用して分散チーム向けにテンプレートセットを一括生成。

* スケジュールに基づいてOTTテンプレートを生成する政府機関や非営利団体のシステム。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}