---
title: XPSをMARKDOWNにレンダリングするAndroidAPI
description: JavaAPIを介してAndroid経由でXPSをMARKDOWNに変換する

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MARKDOWN
otherformats: MHTML XAMLFLOW DOCM PS ODT OTT DOTM FLATOPC DOTX DOT WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java経由でAndroid上のMARKDOWNにXPSをレンダリングする" h2="ソフトウェアをインストールせずにモバイルアプリでXPSをMARKDOWNに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android Java](https://products.aspose.com/total/android-java/)パッケージの2つのAPIを使用して、モバイルアプリにXPSからMARKDOWNへの変換機能を統合できます。まず、[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)を使用してXPSファイルをDOCに変換する必要があります。次に、ワードプロセッシングAPI [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)を使用して、DOCをMARKDOWNにレンダリングできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してAndroidでXPSをMARKDOWNに変換する" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)クラスを使用してXPSファイルを開きます
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-を使用してXPSをDOCに変換します) 方法
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルをロードします。
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))メソッドを使用してドキュメントをMARKDOWN形式で保存し、MARKDOWNを設定しますSaveFormatとして
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/)および[Aspose.Words for Android via Java](https://docs.aspose.com/words)をインストールします。アプリケーションの/java/ install-aspose-words-for-android-via-java /＃install-asposewords-for-android-via-java-from-maven-repository)。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MARKDOWN
outputDocument.save("output.markdown", SaveFormat.MARKDOWN);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidでXPSファイル情報を取得する" %}}
XPSをMARKDOWNに変換する前に、作成者、作成日、キーワード、変更日、件名、タイトルなど、ドキュメントに関する情報が必要になる場合があります。この情報は、変換プロセスの意思決定に役立ちます。強力な[Aspose.PDFforAndroid via Java](https://docs.aspose.com/pdf/androidjava/)APIを使用すると、すべてを取得できます。 XPSファイルに関するファイル固有の情報を取得するには、最初に[getInfo](https：//を使用して[DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo)オブジェクトを取得します。 reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--)メソッド。 DocumentInfoオブジェクトが取得されると、個々のプロパティの値を取得できます。
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidのMARKDOWNドキュメントに文末脚注を挿入する" %}}
ドキュメントの変換とは別に、[Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/)APIを使用して、Androidアプリケーション内に他の多くの機能を追加することもできます。その機能の1つは、MARKDOWNドキュメントに文末脚注と番号を挿入することです。 MARKDOWNドキュメントに脚注または文末脚注を挿入する場合は、DocumentBuilder.InsertFootnoteメソッドを使用してください。このメソッドは、脚注または文末脚注をドキュメントに挿入します。 EndnoteOptionsクラスとFootnoteOptionsクラスは、脚注と文末脚注の番号付けオプションを表します。
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.markdown", SaveFormat.MARKDOWN);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}