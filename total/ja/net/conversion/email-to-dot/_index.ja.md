---
title: EMAILをDOTにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMAILをDOTに変換する
url_ignore: /ja/net/conversion/email-to-dot/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOT
otherformats: DOC TEXT GIF EPUB EMF RTF DOT PS DOTM DOTX SVG PCL WORDML OTT ODT JPEG DOCM DOCX MD PNG FLATOPC TIFF XPS PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOTにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMAILをDOTにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMAILからDOTへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMAILファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOTにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAILをDOTに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)クラスを使用してEMAILファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMAILをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOT形式で保存し、DotをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMAILファイルを解析する" %}}(
EMAILをDOTに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMAILドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOTドキュメントの編集を制限する" %}}
ドキュメントをEMAILからDOTに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMAILファイルをDOTに変換する：ユースケース" %}}
メールファイルは、テキストベースの情報を保存するために適しています。個人の通信やお手伝いとしても最適です。当 chúngがマルチメディアデータと関わる場合には、ドット形式（テキストファイルの拡張子）が必要となります。

メールファイルをドット形式に変換する必要があります。この変換により、以下のような用途で役立つようになります：

**用途:**

*   **個人通信**: メールファイルを分析し、会話の流れやデータのパターンを追跡することができます。
*   **ビジネス通信の最適化**: ビジネスデータを可視化し、戦略を最適化し、ROIを測定することができます。
*   **ドキュメント管理**: インタラクティブなドキュメントを作成し、ユーザー体験をシミュレーションし、ドキュメントの概念を検証することができます。
*   **コンテンツ作成と発信**: 複雑なコンテンツデータを可視化し、記事やブログポスト、研究紙などを表現することができます。
*   **データアーカイーブングとバックアップ**: セキュアなアーカイーブンやレポート、ビジュアライゼーションを作成し、利益関係者に提供することで、より良い決策を支援することがありません。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}