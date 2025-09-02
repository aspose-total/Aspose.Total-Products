---
title: Java経由でEMLをDOCにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMLをDOCに変換するJavaAPI
url_ignore: /ja/java/conversion/eml-to-doc/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOC
otherformats: MD PCL PS JPEG TIFF RTF DOTX PNG DOC DOCM DOCX EPUB DOT WORDML EMF DOTM TEXT FLATOPC OTT SVG XPS GIF ODT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMLをDOCにレンダリングするJavaAPI" h2="サードパーティの依存関係を使用せずに、オンプレミスのJavaAPIを使用してEMLをDOCにエクスポートします" >}}
{{% blocks/products/pf/feature-page-summary %}}
電子メール変換は、Java開発者が[Aspose.Total for Java](https://products.aspose.com/total/java/)を介してJava J2SE、J2EE、J2MEアプリケーションに統合できる強力な機能です。パッケージ内で2つのAPIを使用することにより、サードパーティの依存関係なしに電子メールEMLをDOCに変換できます。まず、Eml Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/)を使用して、EMLファイル形式をHTMLに変換できます。次に、Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用してHTMLをDOCにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="メールをDOCに変換する方法" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)を使用してEMLをHTMLに変換します)) 方法
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してHTMLをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してドキュメントをDOC形式で保存します))メソッドとDOCをSaveFormatとして設定します
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
```
**EMLをDOCに変換**すると、電子メールメッセージが編集可能なMicrosoft Word文書に変換され、報告書、文書化、または共同作業のために電子メールコンテンツを再利用、編集、フォーマットすることが容易になります。

### ✅ 主な使用用途

* 編集可能な形式で重要な電子メールをアーカイブする
* 電子メールコミュニケーションから専門的なレポートを作成する
* Wordで電子メールの契約書や合意事項を編集する
* クライアントとのコミュニケーションをプロジェクト文書に変換する

### ⚙️ 自動化シナリオ

* 電子メールアーカイブをDOCに一括変換して記録管理する
* EMLファイルからビジネスレポートを生成するための自動化パイプライン
* 文書管理システム（DMS）との統合
* 法的およびコンプライアンス文書のワークフロー自動化
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}