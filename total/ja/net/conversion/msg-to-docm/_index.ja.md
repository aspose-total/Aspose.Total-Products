---
title: MSGをDOCMにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをDOCMに変換する
url_ignore: /ja/net/conversion/msg-to-docm/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCM
otherformats: DOCM SVG DOC DOT PCL XPS MD EPUB RTF GIF DOTX PS TEXT FLATOPC WORDML PNG JPEG OTT TIFF PDF DOTM DOCX EMF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOCMにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをDOCMにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからDOCMへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをDOCMにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをDOCMに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
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

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMSGファイルを解析する" %}}(
MSGをDOCMに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOCMドキュメントの編集を制限する" %}}
ドキュメントをMSGからDOCMに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docm", SaveFormat.Docm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをDOCMに変換する：ユースケース" %}}
メッセージファイル（MSG）をドキュメントテンプレートファイル（DOCM）に変換する：あなたのドキュメントマネージャー能力を最大限活用するための鍵となります。

MSGファイルは、Microsoft Outlookで使用されることが多く、メールコンテンツの保存と共有にとどまるべきではありません。協力的な文档編集においては、ドキュメントテンプレート（DOCM）ファイルがチーム管理とバージョン制御を実現するための重要なツールとなります。

MSGファイルをDOCM形式に変換することで、次のような利益があるためです：

**用途：**

* **チーム協力：** MSGファイルをDOCMに変換し、編集可能なドキュメントを作成してチームに共有できるようにし、リアルタイムの協力とフィードバックを容易に実現する。
* **ドキュメントテンプレート管理：** DOCMファイルを使用して、複数のプロジェクトを通じてドキュメントテンプレートを管理し、コンテンツの更新や一貫性を確保する。
* **バージョン制御と追跡：** MSGファイルをDOCMに変換し、内蔵されたバージョン制御機能を活用して、チームが変更を監視し、更新履歴を確認できるようにする。
* **コンテンツの移管と再生：** DOCMファイルを使用して、MSGファイルからメールコンテンツを他のMicrosoft Office アプリケーションに移管し、ドキュメントマネージャーとの一貫性を確保する。
* **セキュリティと合规性：** 强いセキュリティ機能（例：暗号化とアクセス制御）を備えたDOCMファイルに変換し、組織内のポリシーや法規に適合した状態でコンテンツを管理する。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}