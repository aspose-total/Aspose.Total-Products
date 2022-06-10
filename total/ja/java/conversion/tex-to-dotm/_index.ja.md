---
title: TEXをDOTMにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してTEXをDOTMに変換する
url_ignore: /ja/java/conversion/tex-to-dotm/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: DOTM
otherformats: DOT RTF OTT XAMLFLOW FLATOPC ODT DOTX MARKDOWN WORDML PCL MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してTEXをDOTMに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにTEXをDOTMにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、TEXをDOTMに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してTEXファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをDOTMに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEXをDOTMに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してTEXファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してTEXをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをDOTM形式で保存し、DOTMを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://downloads.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
TEXをDOTMに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してTEXを開く必要があります。  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.tex", "password");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してパスワードで保護されたTEXドキュメントを開く" %}}
入力ドキュメントをDOTMファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 DOTMをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-rtf/" name="TEX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-wordml/" name="TEX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-odt/" name="TEX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-flatopc/" name="TEX に FLAにPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-ps/" name="TEX に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-pcl/" name="TEX に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-mhtml/" name="TEX に MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-dotm/" name="TEX に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-ott/" name="TEX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-dotx/" name="TEX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-xamlflow/" name="TEX に XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/tex-to-markdown/" name="TEX に MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}