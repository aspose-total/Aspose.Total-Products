---
title: EMLをWORDにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLをWORDに変換する
url_ignore: /ja/net/conversion/eml-to-word/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: DOC ODT PNG TIFF PDF WORD EMF JPEG TEXT DOT WORDML RTF OTT EPUB MD DOCM DOCX GIF SVG DOTX PCL XPS FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをWORDにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLをWORDにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLからWORDへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをWORDにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLをWORDに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMLをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをWORD形式で保存し、WordをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLファイルを解析する" %}}(
EMLをWORDに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/eml)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したWORDドキュメントの編集を制限する" %}}
ドキュメントをEMLからWORDに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLファイルをWORDに変換する：ユースケース" %}}
EML（電子メール）ファイルは、テキストベースのメッセージを保存するために使用され、個人用のメールやビジネスコミュニケーションで適しています。しかし、フォーマットとレイアウトを制御する必要がある場合、ワードドキュメントはプロフェッショナルなコミュニケーションと協働作業において不可欠です。

EMLファイルをワード形式に変換することは、自分の書き込んだ内容の完全な可能性を引き出すために必要です。この変換が可能にする用途は次の通りです：

**用途（Use Cases）：**

* **ビジネスコミュニケーション**: EMLファイルをフォーマルなビジネスレター、提案、報告書に変換し、プロフェッショナルなトーンで表現することができます。
* **個人用メール管理**: ワードを使用して個人用のメールを管理し、フォルダー、ラベル、カテゴリーを作成し、容易に整理と検索が可能です。
* **ミーティングノートとミニッツ**: EMLファイルをミーティングノートとミニッツに変換し、重要なディスカッションや決意を清潔に記録することができます。
* **テクニカルドキュメント**: ワードを使用してユーザーマニュアル、指南書、テクニカルスペシャリシンが容易に読みやすく表現されるようにします。
* **協働作業編集**: EMLファイルを協働作業用のドキュメントに変換し、チームメンバーや共に働きやすいように、リアルタイムで追跡と修正が可能です。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}