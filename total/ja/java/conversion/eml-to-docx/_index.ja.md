---
title: Java経由でEMLをDOCXにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMLをDOCXに変換するJavaAPI
url_ignore: /ja/java/conversion/eml-to-docx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: MD PDF GIF EPUB SVG PNG ODT XPS OTT DOC TEXT DOCX DOTX RTF PS TIFF DOT EMF FLATOPC WORDML DOTM DOCM JPEG PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMLをDOCXにレンダリングするJavaAPI" h2="サードパーティの依存関係を使用せずに、オンプレミスのJavaAPIを使用してEMLをDOCXにエクスポートします" >}}
{{% blocks/products/pf/feature-page-summary %}}
電子メール変換は、Java開発者が[Aspose.Total for Java](https://products.aspose.com/total/java/)を介してJava J2SE、J2EE、J2MEアプリケーションに統合できる強力な機能です。パッケージ内で2つのAPIを使用することにより、サードパーティの依存関係なしに電子メールEMLをDOCXに変換できます。まず、Eml Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/)を使用して、EMLファイル形式をHTMLに変換できます。次に、Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してHTMLをDOCXにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="メールをDOCXに変換する方法" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)を使用してEMLをHTMLに変換します)) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをDOCX形式で保存します))メソッドとDOCXをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを使用する必要がありますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ 主な使用ケース

* メールを再利用可能なビジネス文書に変換する
* ワード形式でプロジェクト関連のコミュニケーションを共有する
* メールスレッドからフォーマットされたレポートを生成する
* プレゼンテーションや会議のための文書を準備する

## ⚙️ 自動化シナリオ

* 企業レポート用の自動化されたメールからワードへのパイプライン
* アーカイブ用にメールボックス全体をDOCXに変換する
* CRM/ERPシステムとの統合による文書生成
* プロジェクト文書のワークフロー自動化
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}