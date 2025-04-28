---
title: MSGをIMAGEにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをIMAGEに変換する
url_ignore: /ja/net/conversion/msg-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: IMAGE
otherformats: XPS MD PNG DOT EPUB DOCM JPEG GIF ODT PCL DOCX WORDML DOTX TEXT DOC FLATOPC EMF PS TIFF IMAGE RTF PDF SVG OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをIMAGEにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをIMAGEにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからIMAGEへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをIMAGEにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをIMAGEに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
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

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMSGファイルを解析する" %}}(
MSGをIMAGEに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したIMAGEドキュメントの編集を制限する" %}}
ドキュメントをMSGからIMAGEに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをIMAGEに変換する：ユースケース" %}}
MSG（メッセージ）ファイルは、プレインテキストメッセージを保存するのに適した形式です。しかし、ビジュアルコンテンツとの仕事においては、画像が複雑なアイデアやエモーションを伝えるための重要な手段となります。

MSGファイルをイメージフォーマットに変換する必要があります。これにより、視覚的な通信とプレゼンテーションの可能性を完全に活用することが可能になります。この変換が可能なさまざまな用途は以下の通りです：

**用途（Use Cases）：**

*   **ソーシャルメディアでの投稿**: MSGファイルをイメージ形式で利用し、メッセージに画像を追加してエンゲージングなソーシャルメディアポストを作成することができます。
*   **メールマーケティングキャンペーン**: イメージの追加を通じてメールキャンペーンの視覚的な吸引力を高め、読者からの注意を引きつけ、エンゲージメントを促進することができます。
*   **テキストトスピーチプレゼンテーション**: MSGファイルをイメージ形式で利用し、テキストトスピーチ機能を備したインタラクティブなプレゼンテーションを作成することができるため、手指操作なしでのナビゲーションや重要なメッセージの強調が可能になります。
*   **バーチャルアシスタントとチャットボット**: イメージを追加してバーチャルアシスタントのインタラクションに視覚的なキューブを提供し、ユーザー体験を向上させ、レスポンスタイムを短められることができます。
*   **オンライン学習コンテンツの作成**: MSGファイルをイメージ形式で利用し、複雑な概念をイラストレーションとして示すことで学習者とのエンガジェ먼트を高めることができるようになります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}