---
title: EPUBをFLATOPCにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してEPUBをFLATOPCに変換する
url_ignore: /ja/java/conversion/epub-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: FLAT_OPC
otherformats: PS DOT ODT XAMLFLOW RTF OTT DOTX WORDML DOTM PCL MARKDOWN MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してEPUBをFLATOPCに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにEPUBをFLATOPCにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、EPUBをFLATOPCに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してEPUBファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをFLATOPCに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをFLATOPCに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してEPUBファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してEPUBをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをFLATOPC形式で保存し、FLATOPCを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
EPUBをFLATOPCに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してEPUBを開く必要があります。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してパスワードで保護されたEPUBドキュメントを開く" %}}
入力ドキュメントをFLATOPCファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 FLATOPCをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.FLAT_OPC);
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
EPUBをFlat OPC（Flat XML Officeファイル）に変換することは、デジタル出版物からXMLベースのワード処理ファイルを生成するために重要です。Flat OPCは完全にXML駆動の構造を提供し、相互運用性、メタデータ統合、コンテンツの自動化を向上させます。EPUBをFlat OPCに変換することで、出版社、研究者、企業は構造化されたワークフローを実現し、学術報告を簡素化し、長期的なデジタルアーカイブを標準化することができます。

{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}
- **構造化された出版ワークフロー** – 一貫したXMLベースのコンテンツ管理を可能にします。
- **XML駆動の学術報告** – メタデータ豊かなXML構造で研究成果を提供します。
- **メタデータ豊かなアーカイブ** – eBookのコンテンツとメタデータを標準化されたFlat OPCファイルで保存します。
- **研究文書** – 学術出版物を相互運用可能なXMLワード形式に変換します。
- **企業間コンテンツ交換** – プラットフォームやシステム間でスケーラブルな文書共有をサポートします。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}
- **EPUBからFLATOPCへのパイプライン** – eBookをXMLベースのオフィスファイルに自動変換します。
- **自動化されたXML文書生成** – 出版および企業ワークフローを効率化します。
- **メタデータからワードワークフロー** – 構造化されたメタデータを使用可能なワード互換形式に変換します。
- **企業レベルの出版自動化** – 大規模組織全体で文書を標準化します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}