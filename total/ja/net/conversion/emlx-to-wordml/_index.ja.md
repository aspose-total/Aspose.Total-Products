---
title: EMLXをWORDMLにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをWORDMLに変換する
url_ignore: /ja/net/conversion/emlx-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: WORDML
otherformats: MD DOTM EMF DOCX GIF PDF OTT JPEG FLATOPC RTF DOT PNG DOCM SVG PS ODT DOC EPUB DOTX TEXT WORDML PCL XPS TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをWORDMLにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをWORDMLにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからWORDMLへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをWORDMLにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをWORDMLに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをWORDML形式で保存し、WordmlをSaveFormatとして設定します
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
EMLXをWORDMLに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したWORDMLドキュメントの編集を制限する" %}}
ドキュメントをEMLXからWORDMLに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをWORDMLに変換する：ユースケース" %}}
EMLX（電子メールリスト交換ファイル）は、プレインテキスト情報を保存するために使用されるため、シンプルなメールやニュースレターなどのドキュメントを作成するのに適しています。しかし、構造化されたデータの取り扱いにおいては、ワードML形式はフォーマットと表現において必須となる。

EMLXファイルをワードML形式に変換する必要があります。これにより、ドキュメントのフォーマットと表現能力が完全に活用されるようになります。以下に、ワードML形式への変換が実現できる用途を挙げています：

* **ドキュメントパブリッシング**: ワードML形式でニュースレター、ブロチュア、セールスメーションマテリアルなどビジュアル的に魅力あるドキュメントを作成することが可能です。
* **マーケティングマテリアル作成**: ワードML形式を使用してプレスリリース、製品説明、プロモーションフライヤーなどのマーケティングマテリアルをデザインとフォーマットすることができます。
* **ビジネスコレンスランス**: EMLXファイルをワードML形式に変換してプロフェッショナルにフォーマットされたビジネスメール、手書き、レポートを作成することが可能です。
* **教育内容開発**: ワードML形式を使用してインタラクティブな教育コンテンツを開発することができます。例えば、チュートリアル、クイズ、課題などが含まれています。
* **デジタルパブリッシング**: EMLXファイルをワードML形式に変換してエブック、雑誌、他のデジタルパブリケーションにプロフェッショナルなタッチで作成することが可能です。

EMLXファイルをワードML形式に変換することで、高度なフォーマットと表現能力を活用し、より魅力ある且効果的なドキュメントを作成することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}