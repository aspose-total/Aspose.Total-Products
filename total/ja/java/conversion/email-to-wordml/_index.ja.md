---
title: Java経由でEMAILをWORDMLにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMAILをWORDMLに変換するJavaAPI
url_ignore: /ja/java/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD_ML
otherformats: MD FLATOPC PNG DOCM DOC EMF GIF DOT SVG WORDML PS ODT DOTX OTT PDF RTF TEXT PCL XPS JPEG EPUB DOCX DOTM TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMAILをWORDMLにレンダリングするJavaAPI" h2="サードパーティの依存関係を使用せずに、オンプレミスのJavaAPIを使用してEMAILをWORDMLにエクスポートします" >}}
{{% blocks/products/pf/feature-page-summary %}}
電子メール変換は、Java開発者が[Aspose.Total for Java](https://products.aspose.com/total/java/)を介してJava J2SE、J2EE、J2MEアプリケーションに統合できる強力な機能です。パッケージ内で2つのAPIを使用することにより、サードパーティの依存関係なしに電子メールEMAILをWORDMLに変換できます。まず、Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/)を使用して、EMAILファイル形式をHTMLに変換できます。次に、Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してHTMLをWORDMLにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="メールをWORDMLに変換する方法" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)クラスを使用してEMAILファイルを開きます
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)を使用してEMAILをHTMLに変換します)) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをWORDML形式で保存します))メソッドとWORDMLをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}