---
title: EMLをFLATOPCにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLをFLATOPCに変換する
url_ignore: /ja/net/conversion/eml-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: FLATOPC
otherformats: XPS PNG RTF TEXT DOTX OTT DOCX EMF DOCM PS MD PDF DOT DOC SVG EPUB PCL DOTM JPEG WORDML ODT TIFF FLATOPC GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをFLATOPCにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLをFLATOPCにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLからFLATOPCへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをFLATOPCにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLをFLATOPCに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)クラスを使用してEMLファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMLをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをFLATOPC形式で保存し、FlatopcをSaveFormatとして設定します
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
EMLをFLATOPCに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/eml)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したFLATOPCドキュメントの編集を制限する" %}}
ドキュメントをEMLからFLATOPCに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.FlatOpc
document.Save("output.flatopc", SaveFormat.FlatOpc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLファイルをFLATOPCに変換する：ユースケース" %}}
EML（電子メール）ファイルは、テキストベースの通信情報を保存するために使用されます。単純な文書や手紙を作成するための理想的なツールです。しかし、ダイナミックなデータと仕事をする場合、デスクトップパUBLISHINGソフトウェアのようなツールが、文书のレイアウトやデザインを担当する必要があります。

EMLファイルをOffice Word形式に変換することが、文书編集やデザインの可能性を完全に活用するために必要です。この変換により、次のような利益があると考えられます。

**使用事例:**

* ビジネス通信：EMLファイルをプロフェッショナルなビジネス文書（例：手紙、メモ、レポート）を作成するために使用します。
* 個人用の手紙や誕生日カード等の個別的な文书作成：Office Wordを使用します。
* 履歴書やCVを作成するために、EMLファイルをフォーマットし、求職者が職務に応応するために使用します。
* 会議の記録やメモを電子メールでの会話からOffice Wordで作成し、簡単な要約や資料として使用します。
* 文书テンプレートを作成するために、EMLファイルをフォーマットし、常用的なビジネス需要に適した再利用可能なテンプレートとして使用します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}