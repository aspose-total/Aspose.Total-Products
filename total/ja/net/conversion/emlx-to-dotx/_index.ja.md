---
title: EMLXをDOTXにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをDOTXに変換する
url_ignore: /ja/net/conversion/emlx-to-dotx/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOTX
otherformats: OTT DOC PCL EMF DOTM MD DOCX XPS RTF PDF PNG TIFF DOCM DOTX ODT PS FLATOPC TEXT DOT GIF WORDML JPEG SVG EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOTXにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをDOTXにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからDOTXへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOTXにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをDOTXに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
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

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLXファイルを解析する" %}}(
EMLXをDOTXに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOTXドキュメントの編集を制限する" %}}
ドキュメントをEMLXからDOTXに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをDOTXに変換する：ユースケース" %}}
EMXL（電子メール交換言語）ファイルは、メールメッセージ情報を保存するために使用され、静的なメール作成やメッセージングにおいて適用です。しかし、動的データを扱う際には、マイクロソフト・ワードがドキュメントの作成と協力に必要なります。

EMXL ファイルを .docx 形式に変換することは、自分のドキュメント作成や協力機能を最大限活用するための必要手段です。この変換により、次のようなことが可能になります：

**使用例：**

* **ビジネスコミュニケーション**: EMXL ファイルをプロフェッショナルなビジネスメール、レポート、ミーティングノートを作成するために利用します。
* **マーケティングキャンペーン資料**: マイクロソフト・ワードを使用して、マーケティングキャンペーンの資料（ブロシューレ、フライヤー、セールスシートなど）を作成します。
* **プロジェクトマネージメントレポート**: EMXL ファイルをプロジェクトマネージメントレポートを作成するために利用します。例えば、進度更新、タスク割配、リソース割配などの情報を含むレポートです。
* **教育と研究用パペル**: .docx 形式で学術紙、修論、研究ドキュメントを書き、編集し協力するために利用します。
* **協力的なドキュメント作成**: EMXL ファイルを協力的なインタラクティブなドキュメントに変換し、チームメンバーや他者とリアルタイムで共同で働くことが可能になります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}