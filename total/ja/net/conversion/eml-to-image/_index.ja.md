---
title: EMLをIMAGEにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLをIMAGEに変換する
url_ignore: /ja/net/conversion/eml-to-image/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EMF WORDML PDF ODT MD TEXT DOTM DOC DOCX DOT DOCM IMAGE SVG EPUB JPEG RTF PNG XPS GIF PCL PS TIFF DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをIMAGEにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLをIMAGEにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLからIMAGEへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをIMAGEにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLをIMAGEに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMLをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをIMAGE形式で保存し、ImageをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLファイルを解析する" %}}(
EMLをIMAGEに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/eml)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したIMAGEドキュメントの編集を制限する" %}}
ドキュメントをEMLからIMAGEに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLファイルをIMAGEに変換する：ユースケース" %}}
EML (電子メール) ファイルは、テキストベースのメールを保存するために使用され、静的なメールコンテンツを作成するのに適しています。しかし、動的な画像やグラフィックスと働き合わせる場合には、JPEG 形式や PNG 形式のようなビジュアルコミュニケーションに必要な形式が重要になります。

EML ファイルを画像形式に変換することで、視覚的な通信の限界を超えることができます。この変換により、次のような用途で役立ちます：

* **ソーシャルメディア向けのコンテンツ作成**: EML ファイルを加工して、ユーザーが注目に引くソーシャルメディア投稿や画像、グラフィックを作成することができます。
* **EC商店での製品展示**: プロダクトの情報、特徴、利益を視覚的に表現するために画像形式を使用します。
* **デジタルマーケティングキャンペーン**: eye-catching なメールマーケティングキャンペーンやプロモーショナルマテリアル、セールページを作成することができます。
* **ブログや記事のイラストレーション**: 複雑なブログポストやアーティクルの理解を視覚的に支援するために画像形式を使用します。
* **技術ドキュメント**: 技術情報を視覚的に表現するためにEML ファイルを加工します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}