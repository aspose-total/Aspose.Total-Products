---
title: MSGをWORDにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにMSGをWORDに変換する
url_ignore: /ja/net/conversion/msg-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD
otherformats: EMF TEXT SVG XPS PS FLATOPC ODT WORD OTT GIF PCL MD TIFF DOT DOC JPEG PNG WORDML DOTM DOCX PDF DOCM DOTX EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをWORDにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでMSGをWORDにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にMSGからWORDへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、MSGファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをWORDにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSGをWORDに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)クラスを使用してMSGファイルを開きます
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)メソッドを使用してMSGをHTMLに変換します
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

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMSGファイルを解析する" %}}(
MSGをWORDに変換する前に、正しい電子メールを変換していることを確認したい場合は、MSGドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/msg)の[MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したWORDドキュメントの編集を制限する" %}}
ドキュメントをMSGからWORDに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMSGファイルをWORDに変換する：ユースケース" %}}
MSGファイルをWordドキュメントに変換する必要があります。これにより、次のような機能を活用することが可能になります。

**利用例：**

* **コンテンツエディット**：MSGファイルを編集し、変更追跡をするだけでなく、チームメンバーや共有者と協力することができます。
* **リサーチ・アナリза**：Wordで研究データを分析し、視覚化することも可能です。引用文献を作成し、出所をフォーマットすることもできます。
* **ビジネスコミュニケーション**：MSGファイルを用いてプロフェッショナルなビジネスコミュニケーションを作成することができます。提案やレポートを制作することが可能です。
* **教育と研究での執筆**：Wordで学術的な論文を書き、シラバスを作成し、参考文献をフォーマットすることができます。これは学生や研究者向けの役立つような内容です。
* **データドライブンなコンテンツクリエーション**：MSGファイルを用いてデータを基にしたインフォグラフィックやプレゼンテーションを作成することができます。さまざまなアウディエンスに向けて作成することが可能です。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}