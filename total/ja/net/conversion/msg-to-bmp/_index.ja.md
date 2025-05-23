---
title: MSGをBMPにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをBMPに変換する
url_ignore: /ja/net/conversion/msg-to-bmp/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: BMP
otherformats: DOCM GIF EPUB RTF ODT TIFF PNG FLATOPC PS XPS DOC EMF DOTM DOT PDF TEXT WORDML PCL SVG MD OTT JPEG DOTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをBMPにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをBMPにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからBMPへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをBMPにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをBMPに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをBMP形式で保存し、BmpをSaveFormatとして設定します
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
MSGをBMPに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したBMPドキュメントの編集を制限する" %}}
ドキュメントをMSGからBMPに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.bmp", SaveFormat.Bmp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをBMPに変換する：ユースケース" %}}
MSG（メッセージファイル）は、テキストベースのメッセージを保存するために使用され、シンプルな通信プロトコールやアプリケーション間のデータ交換に適した形式です。しかし、イメージベースのデータと仕事をする場合には、ビットマップファイル（BMP）のような画像保存形式が必要となります。

MSGファイルをBMP形式に変換することが求められます。これにより、イメージのビューイングやエディット、ハイレゾリューションのグラフィックスや詳細なテクスチャーを含むビットマップファイルの利用が可能になります。

**用途（Use Cases）：**

* **イメージの表示と編集**: MSGファイルをBMP形式に変換し、画像を表示するだけでなく、エディットすることができるようにします。高分辨率グラフィックスや詳細なテクスチャーを含むビットマップファイルを利用できます。
* **ゲーム開発とデプロイ**: ゲームアセットとしてスプライト、バックグラウンド、エフェクトを保存するためにBMPファイルを使用します。異なるプラットフォームにゲームを展開することが容易になります。
* **ロゴデザインとブランドイング**: MSGファイルをBMP形式に変換し、ベクターサイズのロゴを作成することができます。スケーラブルな高品質のブランドマテリアルを制作するのに適します。
* **ディジタルサイネージとディスプレイ**: ディジタルサイネージでイメージを表示するためにBMPファイルを使用します。メニュー、広告、情報表示など、さまざまな用途に適しています。
* **医療画像と診断**: MSGファイルをBMP形式に変換し、医学的なイメージを視覚化することができます。X-ray、CTスキャン、MRIなどの医療画像を利用し、正確な診断と治療プランを作成するのに役立ちます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}