---
title: OFTをDOCにエクスポートするためのC＃API
description: .NETでMicrosoftWordまたはOutlookを使用せずにOFTをDOCに変換する
url: /ja/net/conversion/oft-to-doc/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOC
otherformats: PS SVG XPS MD TEXT PDF OTT DOTX EMF DOCX RTF DOC PCL ODT JPEG GIF EPUB FLATOPC TIFF DOCM DOTM PNG DOT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEメールをDOCにエクスポート" h2="WordやOutlookを使用せずにWindows、macOS、LinuxでOFTをDOCにレンダリングする.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内にOFTからDOCへの変換機能を追加しようとしている.NET開発者の場合、[Aspose.Total for .NET](https://products.aspose.com/total/net/）ファイル形式操作APIがその方法です。前方。 [Aspose.Oft for .NET](https://products.aspose.com/oft/net/）を使用すると、OFTファイル形式をHTMLに変換できます。その後、[Aspose.Words for .NET](https://products.aspose.com/words/net/）を使用して、HTMLをDOCにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OFTをDOCに変換するC＃API" %}}
1. [MailMessage](https://apireference.aspose.com/oft/net/aspose.oft/mailmessage）クラスを使用してOFTファイルを開きます
2. [保存](https://apireference.aspose.com/oft/net/aspose.oft.mailmessage/save/methods/3）メソッドを使用してOFTをHTMLに変換します
3. [Document](https://apireference.aspose.com/words/net/aspose.words/document）クラスを使用してHTMLをロードします
4. [保存](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4）メソッドを使用してドキュメントをDOC形式で保存し、DocをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.oft");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.doc", SaveFormat.Doc); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でOFTファイルを解析する" %}}
OFTをDOCに変換する前に、正しい電子メールを変換していることを確認したい場合は、OFTドキュメントをロードして解析し、目的のプロパティを確認できます。 [Aspose.Oft for .NET](https://products.aspose.com/oft）の[MapiMessage](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage）クラスを使用する/ net /）API、送信者と受信者の情報を取得できます。たとえば、[SenderName](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage/properties/sendername）プロパティを使用して、変換用の特定の送信者メールを確認できます。  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an OFT file from disk
var outlookMessageFile = MapiMessage.FromFile("message.oft");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介したDOCドキュメントの編集を制限する" %}}
ドキュメントをOFTからDOCに保存するときに、出力ドキュメントを保護する必要がある場合があります。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。これは、他の人がドキュメント内の機密情報を編集するのを防ぐのに役立ちます。 [Aspose.Words for .NET](https://products.aspose.com/words/net/）APIを使用すると、[ProtectionType](https：//apireference.aspose）を使用してコンテンツを制限する方法を制御できます。 com / words / net / aspose.words / propertytype）列挙型パラメーター。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
```cs

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-pcl/" name="MSGからPCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-pdf/" name="MSGからPDFへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-dot/" name="MSG TO DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-flatopc/" name="MSGからFLATOPCへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-jpeg/" name="MSGからJPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-png/" name="MSGからPNGへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-rtf/" name="MSGからRTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-tiff/" name="MSGからTIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-docm/" name="MSG TO DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-ps/" name="MSGからPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-gif/" name="MSG TO GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-xps/" name="MSGからXPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-odt/" name="MSGからODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-docx/" name="MSGからDOCXへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-doc/" name="MSG TO DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-wordml/" name="MSG TO WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-svg/" name="MSGからSVGへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-epub/" name="MSGからEPUBへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-md/" name="MSGからMD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-emf/" name="MSGからEMFへ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-dotm/" name="MSG TO DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-ott/" name="MSG TO OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-dotx/" name="MSG TO DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/msg-to-text/" name="テキストへのMSG" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}