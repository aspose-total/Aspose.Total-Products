---
title: EMLXをDOCXにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをDOCXに変換する
url_ignore: /ja/net/conversion/emlx-to-docx/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: MD PDF SVG EMF WORDML DOT DOCX FLATOPC DOC ODT JPEG GIF PNG OTT RTF TEXT EPUB DOCM PCL PS DOTM TIFF DOTX XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOCXにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをDOCXにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからDOCXへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOCXにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをDOCXに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOCX形式で保存し、DocxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLXファイルを解析する" %}}(
EMLXをDOCXに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOCXドキュメントの編集を制限する" %}}
ドキュメントをEMLXからDOCXに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをDOCXに変換する：ユースケース" %}}
EMLX（電子メール メッセージ エクスチェンジ）ファイルは、テキストベースの情報を保存するために使用され、シンプルなメール作成やニュースレターの作成に適しています。しかし、ダイナミックなデータと仕事をする場合、マイクロソフト ワード ドキュメントが編集や出版に必要になるようになります。

EMLX ファイルを DocX 形式に変換することは、自分のドキュメント エディットنگ 및 パブリッシング 能力を最大限に向上させるために必要です。この変換により、次のような用途で役立ちます：

**用途：**

* **ビジネス メール テンプレート**: EMLX ファイルを DocX 形式に変換し、カスタマイズ可能な ビジネス メール テンプレートを作成することができます。時間を節約し、生産性を向上させることができます。
* **ニュースレターと プレス リリース**: DocX を編集し、ニュースレターやプレス リリースなど、書かれたコンテンツをプロフェッショナルなフォーマットとレイアウトで出版することができます。
* **ミ팅 ミニッツと レジュメ：EMLX ファイルを DocX 形式に変換し、プロフェッショナルな印象을与えるミ팅 ミニッツやレジュメを作成することができます。
* **ソーシャル メディア ポストと コメント：DocX を用いて、ソーシャル メディア ポストやコメントを書き、オーディエンスと交流することができます。
* **テクニカル ライティングと ドキュメンテ이션：EMLX ファイルを DocX 形式に変換し、テクニカル ライティングやドキュメンテ이션を作成することができるようになります。ユーザー나 クラント向けの清潔な指示やガイドを提供することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}