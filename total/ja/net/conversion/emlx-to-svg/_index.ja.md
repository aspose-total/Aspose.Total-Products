---
title: EMLXをSVGにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをSVGに変換する
url_ignore: /ja/net/conversion/emlx-to-svg/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: SVG
otherformats: SVG ODT JPEG DOC WORDML DOTM EMF DOCX DOTX OTT FLATOPC RTF PS XPS GIF PNG MD PCL DOCM TEXT TIFF PDF DOT EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをSVGにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをSVGにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからSVGへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをSVGにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをSVGに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをSVG形式で保存し、SvgをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLXファイルを解析する" %}}(
EMLXをSVGに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したSVGドキュメントの編集を制限する" %}}
ドキュメントをEMLXからSVGに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをSVGに変換する：ユースケース" %}}
**EMLX 変換：インタラクティブ ビジュアライツの可能性を引き出す**

EMLX（Email Message Format）ファイルは、構成されたデータを保存するために使用され、静的な情報やドキュメントを作成するのに適しています。しかし、動的なビジュアライツ作成においては、SVG（Scalable Vector Graphics）形式のようなものが必要となります。

EMLX ファイルを SVG 形式に変換することが必要です。これにより、インタラクティブなビジュアライツとその可能性を完全に引き出せるようになります。この変換によって、次の用途で役立つようにします：

* **ウェブサイトでのインタクティビティー**: ホバー効果やアニメーション、interactive maps 等、動的なウェブサイト要素を作成するために EMLX を SVG に変換します。
* **ソーシャルメディアのエンゲージメント**: ソーシャルメディアデータを可視化し、engagingなインフォグラフィックスやinteractive stories を作成するために SVG を使用します。
* **マーケティング・マテリアル**: interactive marketing materials として、brochures, flyers, presentations 等に EMLX を変換して使用します。
* **データストーリーテリング**: 複雑なデータを可視化し、interactive visualizations およびアニメーションを通じて魅力あるストーリーを作成するために SVG を使用します。
* **ゲームやシミュレーションのための利用**: ゲーム体験を_immersive にするため、SVG を使用して EMLX ファイルを変換し、dynamicなグラフィックスとインタクションを実現します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}