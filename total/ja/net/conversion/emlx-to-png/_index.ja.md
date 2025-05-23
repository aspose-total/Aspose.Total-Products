---
title: EMLXをPNGにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをPNGに変換する
url_ignore: /ja/net/conversion/emlx-to-png/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: PNG JPEG DOCX FLATOPC TEXT OTT XPS WORDML ODT DOTX EPUB DOC PS TIFF RTF GIF MD DOCM SVG EMF DOTM DOT PDF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをPNGにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをPNGにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからPNGへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをPNGにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをPNGに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをPNG形式で保存し、PngをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLXファイルを解析する" %}}(
EMLXをPNGに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したPNGドキュメントの編集を制限する" %}}
ドキュメントをEMLXからPNGに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをPNGに変換する：ユースケース" %}}
EMF（エンハンセッド・メタファイル）形式のファイルは、レイヤー化されたグラフィックス情報を保存するために使用され、静止画面やイラストレーションの作成に最適です。しかし、ダイナミックなデータとの取り組みにおいては、他のフォーマットが必要となり、画像編集やマニピュレーションを実現するのに適しています。

EMF 形式のファイルを PNG 形式に変換することは、自分の画像編集やマニピュレーションの能力を最大限に発揮するための重要な手段です。この変換により、次のような用途が可能になります：

**用途（Use Cases）：**

* **画像編集とマニピュレーション**: EMF ファイルを編集し、画像にテキストやシェイプ、エフェクトを追加することができます。
* **アイコンデザインと開発**: PNG を使用して、スケーラブルなアイコン、ロゴ、グラフィックスを作成することができます。これらは、さまざまなアプリケーションに利用されるべきです。
* **グラフィックスとイラストレーション**: EMF ファイルを PNG に変換して、複雑なイラストレーションやグラフィックスを作成し、出版物などで使用することができます。
* **ウェブとモバイル向きの最適化**: PNG を利用して、ウェブやモバイルデバイス向きに最適化された画像を制作し、高速なロード時間と高品質のビジュアルを実現することができます。
* **データ可視化とレポート作成**: EMF ファイルを PNG に変換して、インタクティブな可視化やレポートを作成し、データドライブされたインスाइटを表示することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}