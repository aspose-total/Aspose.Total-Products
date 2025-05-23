---
title: EMLXをTIFFにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにEMLXをTIFFに変換する
url_ignore: /ja/net/conversion/emlx-to-tiff/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: TIFF
otherformats: TIFF DOTX PNG TEXT PCL ODT PS DOTM PDF GIF WORDML DOCX JPEG EMF OTT DOT FLATOPC MD RTF EPUB XPS DOC SVG DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをTIFFにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでEMLXをTIFFにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にEMLXからTIFFへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/)ファイル形式操作APIがその方法です。前方。 [Aspose.Email for .NET](https://products.aspose.com/email/net/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、HTMLをTIFFにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをTIFFに変換するC＃API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/net/aspose.emlx/mailmessage)クラスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)メソッドを使用してEMLXをHTMLに変換します
3. [Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをTIFF形式で保存し、TiffをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEMLXファイルを解析する" %}}(
EMLXをTIFFに変換する前に、正しい電子メールを変換していることを確認したい場合は、EMLXドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Email for .NET](https://products.aspose.com/email)の[MapiMessage](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage)クラスを使用する/ net /)API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://reference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername)プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NETを介したTIFFドキュメントの編集を制限する" %}}
ドキュメントをEMLXからTIFFに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用すると、[ProtectionType](https：//apireference.aspose)を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype)列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEMLXファイルをTIFFに変換する：ユースケース" %}}
EMLX（電子メールに拡張子を追加した形式）ファイルは、テキストベースのメールメッセージを保存するために使用され、プレインテキストのメールを作成し交換するのに適しています。しかし、イメージが含まれるデータを扱う際には、高品質なイメージングとプリンティングに必要なTiffファイルが重要になります。

EMLXファイルをTiffフォーマットに変換することは、自分のイメージングやプリントイングの可能性を完全に活用するための必要な措置です。この変換により、次のような利益があるためです：

**使用事例:**

*   **プリンティングとアーカイブ:** EMLXファイルをTiff画像に変換し、高解像度のTiff画像を作成し、プリンティング、 アーカイブ、 およびシェアに適したものです。
*   **イメージエディットとマニピュレーション:** Tiffファイルを使用して、イメージデータを編集し、加工することができるため、写真編集、リトゥーチング、 アンド_manipulation_となります。
*   **デジタルサインチャーとバリデーション:** EMLXファイルをTiffファイルに変換し、セキュアなデジタルサインチャーを作成し、電子文書の正当性と完整性を確保することができます。
*   **E-Discoveryとコンフォーマンス:** Tiffファイルを使用して、E-Discoveryデータを管理し、規制的な要件や業界の基準に適したことになります。
*   **芸術的とデザインの応用:** EMLXファイルをTiff画像に変換し、ユニークなデジタルアートを作成することができるため、Tiff画像をキャンバスとして芸術的表現やデザインの実験に使用することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}