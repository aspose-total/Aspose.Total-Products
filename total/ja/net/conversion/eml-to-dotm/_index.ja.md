---
title: EMLをDOTMにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLをDOTMに変換する
url_ignore: /ja/net/conversion/eml-to-dotm/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOTM
otherformats: DOCX PDF DOC PCL JPEG FLATOPC TIFF TEXT DOCM PS EPUB SVG DOTX DOTM ODT MD DOT RTF GIF XPS EMF WORDML OTT PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOTMにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLをDOTMにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLからDOTMへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOTMにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLをDOTMに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMLをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOTM形式で保存し、DotmをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLファイルを解析する" %}}(
EMLをDOTMに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/eml)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOTMドキュメントの編集を制限する" %}}
ドキュメントをEMLからDOTMに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLファイルをDOTMに変換する：ユースケース" %}}
EML（電子メール）ファイルは、テキストベースのメッセージを保存するために使用され、シンプルな通信にとって理想的です。しかし、複雑なデータやビジュアリゼーションとの取り組みにおいて、DOTM形式のようなフォーマットはプレゼンテーションや協力作業にとって不可欠です。

EMLファイルをDOTM形式に変換することは、プレゼンテーションや協力作業の完全な潜力を引き出すために必要です。この変換により、次のような用途が実現されます：

**用途：**

* **営売チームの協力**: 売り担当チームメンバーやクライアント向きのリポート、顧客情報を共有し、より良い意思決定に繋げるためにEMLファイルをDOTM形式で共有します。
* **マーケティングチームのアイデア回収**: マーケティングアイデアやキャンペーンデータを可視化し、リアルタイムで同僚と新しい戦略について-discussするためにDOTMを使用します。
* **ビジネスパートナーシップの進捗管理**: 共同ビジネス提案を作成し、進捗を追跡し、パートナーと共有情報を交換するためにEMLファイルをDOTM形式で共有します。
* **研究分野での協力**: 複雑な研究結果をプレゼンテーションし、共同研究論文を作成し、データをペアレビューするためにDOTMを使用します。
* **顧客フィードバックの分析**: 顧客のフィードバックを分析し、感情傾向を追跡し、顧客コミュニケーションにおけるトレンドを识別するためにEMLファイルをDOTM形式で共有します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}