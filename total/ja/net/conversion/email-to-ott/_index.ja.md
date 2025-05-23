---
title: EMAILをOTTにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMAILをOTTに変換する
url_ignore: /ja/net/conversion/email-to-ott/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: OTT
otherformats: PDF DOTX DOCM MD PCL PNG FLATOPC XPS WORDML ODT DOTM EMF TEXT SVG JPEG GIF OTT DOCX PS TIFF RTF DOT DOC EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをOTTにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMAILをOTTにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMAILからOTTへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMAILファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをOTTにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAILをOTTに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)クラスを使用してEMAILファイルを開きます
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)メソッドを使用してEMAILをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをOTT形式で保存し、OttをSaveFormatとして設定します
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
EMAILをOTTに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMAILドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したOTTドキュメントの編集を制限する" %}}
ドキュメントをEMAILからOTTに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMAILファイルをOTTに変換する：ユースケース" %}}
メールファイルをOTT（Over-the-Top）コンテンツに変換する：エンゲージメントとリビードゥーストリームズを引き出す  
メールファイルは、個別のメッセージを保存するために使用され、ダイナミックなコンテンツ作成に向けて理想的なツールです。しかし、動態的内容を扱う際には、視覚的に配信されるプラットフォームであるOTTが必要となり、観客を引きつけつつリビードゥーストリームズを生産することが可能になります。

メールファイルをOTT形式に変換することは、エンゲージメントとリビードゥーストリームズの潜在可能性を完全に引き出すことができるためです。この変換により、次のような利益を実現できます：  

**用途：**

* **個別のストーリーテリング**: メールファイルを利用して、ユーザー情報を活用した個別のビデオストーリーを作成し、エンゲージメントとリテンションを高めることが可能です。  
* **インターアクティブ・アドバタイジング**: OTTを使用して、ユーザーとの実시간的な反応を測定できるインターアクティブな広告を作成し、メーグンブランドの効果を評価することができます。  
* **ブランデッド・エンターテインメント**: メールファイルを利用して、ブランド固有のコンテンツシリーズを作成し、ダイナミックでストーリーテリングを行うことで観客を魅覚することが可能です。  
* **カスタマー・レラーションシップ・マネージメント**: OTTを使用して、カスタマーのオンボーディング、サポート、フィードバックに適した個別のビデオメッセージを作成し、忠誠度とリテンションを高めることが可能です。  
* **サブスクリプションベースのリビードゥーストリームズ**: メールファイルを利用して、サブスクリプション制でユーザーにエクスクルスイヴコンテンツや体験を提供し、リビードゥーストリームズを生産することが可能です。  

メールファイルをOTT形式に変換することで、エンゲージメント、リビードゥーストリームズの 增加、そしてユーザーとの深い結び付けが可能になります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}