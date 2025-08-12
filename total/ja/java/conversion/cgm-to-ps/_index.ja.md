---
title: CGMをPSにエクスポートするJavaAPI
description: オンプレミスのJavaAPIを使用してCGMをPSに変換する
url_ignore: /ja/java/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML MARKDOWN ODT DOT WORDML OTT RTF PS FLATOPC DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してCGMをPSに変換する" h2="オンプレミスのJavaAPIを使用して、サードパーティのアプリケーションを使用せずにCGMをPSにレンダリングする" >}}
{{% blocks/products/pf/feature-page-summary %}}
2つの簡単な手順を使用して、CGMをPSに変換できます。まず、[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)を使用してCGMファイルをDOCにレンダリングする必要があります。その後、強力なドキュメント処理API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、DOCをPSに変換できます。どちらのAPIも、[Aspose.Total for Java](https://products.aspose.com/total/java/)パッケージに含まれています。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをPSに変換するJavaAPI" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してCGMファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してCGMをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをPS形式で保存し、PSを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できます[Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)と[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)あなたのpom.xmlの。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
CGMをPSに変換している間、ドキュメントがパスワードで保護されている場合でも、PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)を使用してドキュメントを開くことができます。暗号化されたファイルを開くには、[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Javaを介してパスワードで保護されたCGMドキュメントを開く" %}}
入力ドキュメントをPSファイル形式で保存するときに、ファイルシステムの代わりにデータベースにドキュメントを保存することもできます。データベースとの間でDocumentオブジェクトの保存と取得を実装する必要がある場合があります。これは、任意のタイプのコンテンツ管理システムを実装する場合に必要になります。 PSをデータベースに保存するには、多くの場合、ドキュメントをシリアル化してバイト配列を取得する必要があります。これは、[Aspose.Words for Java](https://products.aspose.com/words/Java/)APIを使用して実行できます。バイト配列を取得したら、SQLステートメントを使用してデータベースに格納できます。 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
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
{{% blocks/products/pf/feature-page-summary %}}
```
CGM（Computer Graphics Metafile）をPS（PostScript）に変換することは、正確で高品質な印刷物やプロの出版物を実現する上で重要なステップです。PostScriptのデバイス非依存形式により、複雑なベクトルグラフィックス、エンジニアリング図面、技術イラストなどが印刷機や出版システムに転送されても正確性と忠実度を保持します。これにより、一貫性のある、スケーラブルで印刷に適した出力を必要とする産業にとって、CGMからPSへの変換は欠かせないものとなります。

## ✅ 主な使用用途
- **産業用ベクトル印刷** – 製造、エンジニアリング、建築文書向けに鋭い、スケーラブルな技術図面を作成します。
- **PostScriptベースシステムで技術イラストをアーカイブ** – 長期アクセシビリティと印刷互換性に最適化された形式でベクトルアセットを保存します。
- **タイプセット用のCGM図を準備** – プロのページレイアウトやタイプセットワークフローにシームレスに統合されるようにします。
- **物理的な文書制作** – マニュアル、カタログ、大形技術チャート向けの印刷可能なファイルを生成します。

## ⚙️ 自動化シナリオ
- **Javaベースの印刷ストリームジェネレータ** – 企業向け印刷ワークフローにおいて、プログラムでCGMファイルを高解像度のPS出力に変換します。
- **ベクトルからPostScriptへのバッチ変換ツール** – 大規模な変換プロセスを自動化し、広範なグラフィックアーカイブを効率的に処理します。
- **出版パイプラインの統合** – CGMからPSへの変換を自動化された文書レンダリングやプロの出版システムに組み込み、一貫性のある高品質な結果を得ます。
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}