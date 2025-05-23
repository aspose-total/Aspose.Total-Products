---
title: EMAILをRTFにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMAILをRTFに変換する
url_ignore: /ja/net/conversion/email-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: PS TIFF EPUB SVG WORDML OTT PNG JPEG XPS GIF MD EMF ODT TEXT DOTX PCL FLATOPC DOTM DOCM DOCX RTF DOT DOC PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをRTFにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMAILをRTFにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMAILからRTFへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMAILファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをRTFにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAILをRTFに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)クラスを使用してEMAILファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMAILをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをRTF形式で保存し、RtfをSaveFormatとして設定します
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
EMAILをRTFに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMAILドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したRTFドキュメントの編集を制限する" %}}
ドキュメントをEMAILからRTFに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMAILファイルをRTFに変換する：ユースケース" %}}
**メールファイルからリッチテキストフォーマット（RTF）ファイルへの変換**

メールファイルは、テキストベースのコンテンツを保存するための形式で使用されます。これにより、シンプルなメッセージやコミュニケーションに適したツールとなりますが、フォーマットとレイアウトについては、プロフェッショナルな見た目やプレゼンテーションの可能性を活かすためにRTFファイルが必要になります。

メールファイルをRTF形式に変換することは、ドキュメントのビジュアル・アペリエンスとプレゼンテーション能力を最大限に引き立てることができるためです。この変換により、以下のような用途で役立つようになります：

**利用事例:**

* **プロフェッショナルコレンスペンシル:** メールファイルをRTF形式に変換して、視覚的に魅力ある手紙やメモ、正式な通信を作成することができます。
* **ビジネスリポート作成:** RTF形式でフォーマットされたレポート、提案、プレゼンテーションを制作し、クライアントや株主、管理者向けに配布することができます。
* **マーケティングマテリアル:** メールファイルをRTF形式に変換して、目を引くニュースレター、ブロシューレ、宣伝資料を作成することができます。
* **学術研究パペラ:** RTF形式でフォーマットされた研究報告、修論、博士論文を作成し、レイアウトとフォーマットが精确に表現されることができます。
* **テクニカルドキュメント:** メールファイルをRTF形式に変換して、ユーザーマニュアル、インストラクションガイド、ソフトウェアの技術ドキュメントを作成することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}