---
title: EMAILをDOTXにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMAILをDOTXに変換する
url_ignore: /ja/net/conversion/email-to-dotx/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOTX
otherformats: PDF DOCX GIF DOTX PCL PNG OTT SVG DOTM EMF RTF TIFF DOCM ODT EPUB PS FLATOPC XPS MD WORDML DOC JPEG TEXT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOTXにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMAILをDOTXにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMAILからDOTXへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMAILファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOTXにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAILをDOTXに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)クラスを使用してEMAILファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMAILをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOTX形式で保存し、DotxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMAILファイルを解析する" %}}(
EMAILをDOTXに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMAILドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOTXドキュメントの編集を制限する" %}}
ドキュメントをEMAILからDOTXに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMAILファイルをDOTXに変換する：ユースケース" %}}
メールをマイクロソフト オフィス ワード ドキュメント ファイル（.docx）に変換する必要があります。以下の用途で役立つお手伝いが大きいです：

* **プロフェッショナルな文書作成**: ビジネスメーティング、提案、交渉等の正式なドキュメントやレポートを作成するために。
* **契約や合意のレビュー**: 契約、合意、法的に結束するドキュメントをレビュー、編集、署名するために。
* **ミーティングのメモとノート**: ミーティングの詳細を正確に記録し、チームでの協力作業에適したアクションアイテムを作成するために。
* **学術的なレポートやエッセイの書き方**: リサーチーパーやエッセーを容易にフォーマットして書くために。
* **ビジネスヘッドとテンプレート**: プロフェッショナルなビジネスヘッド テンプレート、ニュースレター等を作成するために。

メールをマイクロソフト オフィス ワード ドキュメント ファイルに変換することが多くの利益をもたらします。具体的には以下のようなメリットがあります：

* **読みやすさとフォーマットの向上**
* **共同作業や編集が容易になる**
* **ドキュメントの整理と検索が向上する**
* **プロフェッショナルな印象を与えるため**
* **ドキュメントの共有と配布がスムーズになる**
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}