---
title: EMAILをEMFにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMAILをEMFに変換する
url_ignore: /ja/net/conversion/email-to-emf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EMF
otherformats: XPS OTT DOTM EPUB GIF TEXT PCL DOT PS PDF DOTX ODT RTF DOCX DOCM PNG WORDML EMF JPEG SVG TIFF DOC FLATOPC MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをEMFにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMAILをEMFにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMAILからEMFへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMAILファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをEMFにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAILをEMFに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)クラスを使用してEMAILファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMAILをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをEMF形式で保存し、EmfをSaveFormatとして設定します
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

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMAILファイルを解析する" %}}(
EMAILをEMFに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMAILドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したEMFドキュメントの編集を制限する" %}}
ドキュメントをEMAILからEMFに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMAILファイルをEMFに変換する：ユースケース" %}}
メールは、テキストベースの情報を保存するために使用され、メッセージの送受信に適しています。ただし、イメージデータと関わる場合には、EMF形式のようなフォーマットは、グラフィックスのレンダリングや印刷において重要な役割を果たします。したがって、メールをEMF形式に変換する必要があります。これにより、グラフィックスのレンダリングや印刷の可能性を完全に活用することができます。

以下の用途（Use Cases）に該当する内容が実現されます：

- **Marketing Materials：** コンバータブルマーケティングマテリアルやブロシャー、フライヤーの作成に使用されます。
- **Instructional Guides：** 技術的なプロセスのステップバイステップの指示やマニュアルを作成するのに適しています。
- **Technical Drawings：** 建築、エンジニアリング、構造工事のプロジェクト向けに正確なテクニカルドローイングやブループリントを作成することができます。
- **Graphic Designs：** 高品質なグラフィックデザイン、ロゴ、アイコンなど、ディジタルディスプレイ、広告、出版物向けの作成に使用されます。
- **Educational Content：** インタラクティブな教育コンテンツ、プレゼンテーションスライドショウ、クイズやシミュレーションなどを作成するのに適しています。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}