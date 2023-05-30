---
title: Java経由でEMLXをBMPにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMLXをBMPに変換するJavaAPI
url_ignore: /ja/java/conversion/emlx-to-bmp/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: BMP
otherformats: WORDML MD DOCX DOTM SVG ODT PNG JPEG EPUB PDF PS TEXT GIF XPS OTT DOCM PCL DOTX DOC TIFF DOT EMF FLATOPC RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMLXをBMPにレンダリングするJavaAPI" h2="サードパーティの依存関係を使用せずに、オンプレミスのJavaAPIを使用してEMLXをBMPにエクスポートします" >}}
{{% blocks/products/pf/feature-page-summary %}}
電子メール変換は、Java開発者が[Aspose.Total for Java](https://products.aspose.com/total/java/)を介してJava J2SE、J2EE、J2MEアプリケーションに統合できる強力な機能です。パッケージ内で2つのAPIを使用することにより、サードパーティの依存関係なしに電子メールEMLXをBMPに変換できます。まず、Emlx Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/)を使用して、EMLXファイル形式をHTMLに変換できます。次に、Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してHTMLをBMPにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="メールをBMPに変換する方法" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)クラスを使用してEMLXファイルを開きます
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)を使用してEMLXをHTMLに変換します)) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをBMP形式で保存します))メソッドとBMPをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}