---
title: EMLをEPUBにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLをEPUBに変換する
url_ignore: /ja/net/conversion/eml-to-epub/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EPUB
otherformats: DOCM PCL PNG JPEG TIFF FLATOPC MD DOTM PS DOT DOCX EMF DOC WORDML ODT TEXT EPUB SVG OTT DOTX GIF RTF PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをEPUBにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLをEPUBにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLからEPUBへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをEPUBにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLをEPUBに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMLをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをEPUB形式で保存し、EpubをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLファイルを解析する" %}}(
EMLをEPUBに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/eml)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したEPUBドキュメントの編集を制限する" %}}
ドキュメントをEMLからEPUBに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLファイルをEPUBに変換する：ユースケース" %}}
EML（電子メールファイル）は、テキストベースの情報を保存するために使用され、個人通信や協働作業に適しています。しかし、構成済みデータと多媒体コンテンツを扱う場合には、EPUB（電子出版フォーマット）が必要となり、デジタルパブリッシングや配布に適したものになります。

EMLファイルをEPUBフォーマットに変換することは、自分のデジタルコンテンツやパブリッシング能力を最大限発揮するための重要な手段です。この変換により、次のような利益があるとおりです：

**用途（Use Cases):**

* **デジタル出版**: EMLファイルをEPUBフォーマットに変換し、interactiveなデジタルパブリケーション、雑誌、ニュースレターなどの作成が可能になり、さまざまなデバイスでアクセスできるようにします。
* **電子書籍作成**: EPUBを使用してEMLファイルを電子書籍に変換し、エレクトリックリーダー、タブレット、スマートフォンなどで読める形式にすることができます。
* **ブログ記事出版**: EMLファイルをEPUBフォーマットに変換し、構成済みのフォーマットでブログ記事を公開することができるようにします。これにより発見性やアクセス性が向上します。
* **研究記事作成**: EMLファイルをEPUBフォーマットに変換して研究記事を作成し、容易に共有や引用が可能になるようにします。
* **ドキュメント協働作業**: EMLファイルをEPUBフォーマットに変換し、編集可能なドキュメントを作成し、他人と共有し、フィードバックを受けることができるようにします。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}