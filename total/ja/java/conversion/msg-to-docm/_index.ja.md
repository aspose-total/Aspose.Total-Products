---
title: Java経由でMSGをDOCMにエクスポートする
description: MicrosoftWordやOutlookを使用せずにMSGをDOCMに変換するJavaAPI
url_ignore: /ja/java/conversion/msg-to-docm/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCM
otherformats: FLATOPC DOTX PCL DOC EPUB PS RTF GIF TIFF EMF DOT ODT PDF XPS TEXT SVG WORDML MD DOCX DOCM PNG OTT JPEG DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MSGをDOCMにレンダリングするJavaAPI" h2="サードパーティの依存関係を使用せずに、オンプレミスのJavaAPIを使用してMSGをDOCMにエクスポートします" >}}
{{% blocks/products/pf/feature-page-summary %}}
電子メール変換は、Java開発者が[Aspose.Total for Java](https://products.aspose.com/total/java/)を介してJava J2SE、J2EE、J2MEアプリケーションに統合できる強力な機能です。パッケージ内で2つのAPIを使用することにより、サードパーティの依存関係なしに電子メールMSGをDOCMに変換できます。まず、Msg Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/)を使用して、MSGファイル形式をHTMLに変換できます。次に、Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してHTMLをDOCMにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="メールをDOCMに変換する方法" %}}
1. [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)を使用してMSGをHTMLに変換します)) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをDOCM形式で保存します))メソッドとDOCMをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCM
document.save("output.docm", SaveFormat.DOCM);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}