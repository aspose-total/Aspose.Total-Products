---
title: EMLXをEPUBにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをEPUBに変換する
url_ignore: /ja/net/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: GIF OTT PCL PS EMF RTF DOCM TEXT XPS PNG DOCX DOT EPUB ODT MD FLATOPC DOTM DOTX DOC JPEG WORDML PDF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをEPUBにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをEPUBにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからEPUBへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをEPUBにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをEPUBに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをEPUB形式で保存し、EpubをSaveFormatとして設定します
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

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLXファイルを解析する" %}}(
EMLXをEPUBに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
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
{{% blocks/products/pf/feature-page-section  h2=".NETを介したEPUBドキュメントの編集を制限する" %}}
ドキュメントをEMLXからEPUBに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをEPUBに変換する：ユースケース" %}}
EMLX（電子メールで用いられるヘッダー形式）ファイルは、メール情報を保存するために使用され、静的なメールやメッセージアーカイブを作成するのに適しています。しかし、動態的コンテンツを扱う場合には、ePUBフォーマットが電子出版やオンラインコンテンツの配布に不可欠なとなります。

EMLXファイルからePUBフォーマットへの変換は、自分の電子出版やオンラインコンテンツ配布の潜在的な可能性を完全に活用するために必要です。この変換により、以下のような利益があるとになります：

**利用事例:**

* **電子出版:** EMLXファイルをePUBフォーマットに変換して、さまざまなデバイスで閲覧できるinteractive電子雑誌や新聞、書籍を作成することができます。
* **オンライン学習コンテンツの配布:** ePUBを使用して、オンラインカース、チュートリアル、教育材料を公開し、学生やプロの学習体験を向上させることができます。
* **オンライン記事の配布:** EMLXファイルをePUBに変換して、視覚的におすすめな記事、ストーリー、ブログ記事を作成し、オンラインでの関心度と読者満足度を高めることができます。
* **電子漫画や小説の配布:** ePUBを使用して、電子漫画、小説、そしてinteractiveストーリーテリングを提供することができるので、読者に独自なリーディング体験を提供することができます。
* **ウェブコンテンツのシンジケーション:** EMLXファイルをePUBに変換して、ウェブ上で動態的なコンテンツとして記事、製品説明、カスタマー テストモーニャーを作成し、ウェブサイトでのユーザー関心度とコンバージョンレートを向上させることができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}