---
title: MSGをOTTにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをOTTに変換する
url_ignore: /ja/net/conversion/msg-to-ott/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: OTT
otherformats: FLATOPC DOTX PNG RTF EPUB GIF MD WORDML ODT PS EMF PDF JPEG DOCM DOT DOCX SVG DOC PCL OTT DOTM TEXT XPS TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをOTTにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをOTTにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからOTTへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをOTTにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをOTTに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをOTT形式で保存し、OttをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMSGファイルを解析する" %}}(
MSGをOTTに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したOTTドキュメントの編集を制限する" %}}
ドキュメントをMSGからOTTに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをOTTに変換する：ユースケース" %}}
MSG（メッセージフォーマット）ファイルは、テキストベースの情報を保存するために使用されます。これにより、ネットワーク上でメッセージを送受けすることが容易になります。しかし、多メディアデータを扱う際には、オーバー・ザ・トップ（OTT）サービスの利用が必要となり、ビデオストリーミングやコンテンツの配送を行うのに適しています。

MSGファイルをOTTフォーマットに変換することが必要です。これにより、次のような利益があると考えられます：

**用途：**

* **ビデオストリーミング最適化**: MSGファイルを分析し、視聴者とのエンゲージメントを追跡し、再生品質を最適化することができます。
* **コンテンツリコメンデーションエンジン**: OTTフォーマットを利用して、ユーザーに個別的なコンテンツリコメンダクションを行い、ユーザー体験を向上させ、視聴率を高めることができます。
* **ソーシャルメディアの統合**: MSGファイルを利用して、ソーシャルプラットフォームとOTTサービスの連携をし、ユーザーのエンゲージメントを高めることができます。
* **ライブイベントの放送**: OTTフォーマットを利用して、ライブイベントを配送し、リアルタイムでのユーザーとの交流を可能にし、イミュersiveなビューイング体験を提供することができます。
* **データアナリティックスとインスパイト**: MSGファイルを利用して、OTTサービスのデータを分析し、ユーザーの行動を追跡し、ビジネス成長に有利な洞察を得ることができるようにします。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}