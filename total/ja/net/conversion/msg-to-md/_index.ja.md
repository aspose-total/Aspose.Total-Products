---
title: MSGをMDにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをMDに変換する
url_ignore: /ja/net/conversion/msg-to-md/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: MD
otherformats: SVG TIFF FLATOPC EMF WORDML DOTX ODT PS PCL PDF OTT GIF DOC PNG TEXT DOTM JPEG DOT DOCM RTF MD EPUB XPS DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをMDにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをMDにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからMDへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをMDにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをMDに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをMD形式で保存し、MdをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMSGファイルを解析する" %}}(
MSGをMDに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したMDドキュメントの編集を制限する" %}}
ドキュメントをMSGからMDに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをMDに変換する：ユースケース" %}}
メッセージファイル（MSG）は、プレーンテキストメッセージを保存するのに適した形式で、シンプルなメッセージや通知の送受信に最適です。しかし、より構造化されたデータとの取り組みにおいては、マークダウン形式のファイルが情報のフォーマットとプレゼンテーションに不可欠になります。

MSGファイルをマークダウン形式に変換する必要があります。これにより、メッセージのフォーマットとプレゼンテーションの可能性を最大限活用することができます。この変換が可能にする機能は以下のような用途で役立ちます：

**用途（Use Cases）：**

* **ブログ記事のフォーマットting**: MSGファイルをフォーマットしたブログ記事を作成し、ヘッダー、段落、リストなどを含む形式にします。
* **メールテンプレート**: マークダウン形式でメールテンプレートを作成し、プロフェッショナルな見た目を持つメッセージを容易に送信することができます。
* **チャットボットメッセージ**: MSGファイルをフォーマットしたチャットボットの会話を制作し、マークダウン形式でチャットログやレスポンスを表示することができます。
* **ドキュメント作成**: 技術的なドキュメント、ガイド、チュートリアル、ユーザーマニュアルなどをマークダウン形式で作成し、フォーマットします。
* **ソーシャルメディア投稿**: MSGファイルをフォーマットしたソーシャルメディア投稿を作成し、画像、リンク、ハッシュタグなどを含む形式にします。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}