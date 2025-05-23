---
title: MSGをPNGにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをPNGに変換する
url_ignore: /ja/net/conversion/msg-to-png/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOCX XPS WORDML DOT SVG TIFF OTT ODT EMF FLATOPC EPUB DOC GIF TEXT MD PDF DOTX PNG RTF PCL PS DOCM JPEG DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをPNGにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをPNGにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからPNGへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをPNGにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをPNGに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
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

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMSGファイルを解析する" %}}(
MSGをPNGに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したPNGドキュメントの編集を制限する" %}}
ドキュメントをMSGからPNGに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをPNGに変換する：ユースケース" %}}
メッセージ（MSG）ファイルは、テキストベースのメッセージを保存するために使用され、テキストデータの送受が最適なものです。しかし、ビジュアルコンテンツとの組み合わせにおいて、PNG形式の画像が静的なグラフィックスやイラストレーションを作成する必要があります。

MSGファイルのPNGフォーマットへの変換は、視覚表現と分析能力を最大限に活用するための重要な手段です。この変換により、次のような利益があるためです：

**使用事例:**

* **ソーシャルメディアでのコンテンツシェア:** MSGファイルをPNG形式で共有し、画像や動画を加えることでソーシャルプラットフォーム（例：Facebook, Twitter, Instagram）上でメッセージをシェアすることが可能です。
* **テキストからイメージの合成:** PNGを使用して、テキスト入力からイメージを生成し、プレゼンテーション、レポート、またはマーケティング材料にビジュアル的に魅せることができます。
* **チャットボットの組み込み:** MSGファイルをPNG形式で利用し、メッセージングアプリ（例：Slack, LINE）とチャットボットを統合することで、ユーザーがbotと交互できるほか、画像や動画を視覚的に提供することができます。
* **ドキュメント生成:** PNGを使用して、ビジュアルに富むドキュメントを作成し、例えばダイアグラム、インフォグラフィック、またはスクリーンショットを含むinteractiveドキュメントを生成することができるため、複雑な情報の理解を容易くします。
* **メールニュースレターのデザイン:** MSGファイルをPNG形式で利用し、メールニュースレターに画像、テキスト、そしてその他のマルチメディア要素を含むビジュアル的なデザインを作成することができるため、ユーザーの関心を引きつけ、コンバージョン率を向上させることができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}