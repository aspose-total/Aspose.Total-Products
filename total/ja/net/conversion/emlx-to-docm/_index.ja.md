---
title: EMLXをDOCMにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをDOCMに変換する
url_ignore: /ja/net/conversion/emlx-to-docm/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOCM
otherformats: DOC OTT PNG EPUB DOT DOCM MD DOCX PCL PDF PS GIF FLATOPC WORDML DOTX DOTM TIFF SVG ODT TEXT JPEG EMF XPS RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOCMにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをDOCMにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからDOCMへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOCMにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをDOCMに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOCM形式で保存し、DocmをSaveFormatとして設定します
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
EMLXをDOCMに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOCMドキュメントの編集を制限する" %}}
ドキュメントをEMLXからDOCMに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docm", SaveFormat.Docm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをDOCMに変換する：ユースケース" %}}
EMLX（電子メッセージに大きな添削ファイル）形式は、電子メッセージに関連する情報を保存するために使用され、静的な電子メッセージや添削物の作成に向けて理想的に適合しています。しかし、動態的データと働く場合には、Microsoft Office アプリケーションであるWordなどのドキュメントの視覚化と分析が必要なため、EMLX ファイルを DOCM（ドキュメント テンプレート） 形式に変換することが求められます。

EMLX ファイルを DOCM 形式に変換することは、自分の文書作成や編集能力を最大限に活用するための必要な措置です。この変換により、次のような利益があると言います：

**使用事例：**

* **テンプレート開発**: EMLX ファイルを利用してカスタム ドキュメント テンプレートを作成し、再生的なタスクを自動化し、効率性を向上させることができます。
* **メール オートメーション**: DOCM を用いて自動化されたメール ワークフローを作成し、リマインド、通知、重要な情報の送信を行うことが可能です。
* **ドキュメント コラボレーション**: EMLX ファイルを DOCM に変換して共有するテンプレートを作成し、チームメンバーや他者とのリアルタイム コラボレーションとフィードバックを促進することができます。
* **コンテンツ マネージメント**: 大規模なドキュメント、例えばポリシー、手順書、法規情報などを管理し、更新することができるようになります。
* **セキュリティと合规性**: EMLX ファイルを DOCM に変換して安全で合规的なドキュメントを作成し、機密情報を保護し、業界基準に適合するようにすることができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}