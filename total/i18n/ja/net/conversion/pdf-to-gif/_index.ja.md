---
title: PDFをGIFにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにPDFをGIFに変換する
url: /ja/net/conversion/pdf-to-gif/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: GIF
otherformats: DOTM ODT XAMLFLOW GIF DOT RTF MHTML WORDML PS OTT MARKDOWN PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でPDFをGIFにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のGIFにPDFをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET]（https://products.aspose.com/total/net/）は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET]（https://products.aspose.com/pdf/net/）を使用すると、PDFファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET]（https://products.aspose.com/words/net/）を使用して、DOCをGIFにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDFをGIFに変換するC＃API" %}}
1. [ドキュメント]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスを使用してPDFファイルを開きます
2. [保存]（https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5）メソッドを使用してPDFをドキュメントに変換します
3. Aspose.Wordsの[Document]（https://apireference.aspose.com/words/net/aspose.words/document）クラスを使用してDocファイルをロードします
4. [保存]（https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4）メソッドを使用してドキュメントをGIF形式で保存し、GifをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード]（https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.pdf");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.gif", SaveFormat.Gif);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してPDFファイルを復号化する" %}}
PDFをGIFに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）オブジェクトを作成し、所有者のパスワードを使用してPDFを開く必要があります。その後、Documentオブジェクトの[Decrypt]（https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt）メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
```cs


Document document = new Document("Decrypt.pdf", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用GIF-ファイルを作成" %}}
GIFを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET]（https://products.aspose.com/words/net/）APIを使用して実行できます。 [ProtectionType]（https://apireference.aspose.com/words/net/aspose.words/protectiontype）列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
```cs

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-ott/" name="PDF に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-mhtml/" name="PDF に MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-wordml/" name="PDF に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-dot/" name="PDF に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-odt/" name="PDF に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-rtf/" name="PDF に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-ps/" name="PDF に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-flatopc/" name="PDF に FLAにPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-pcl/" name="PDF に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-markdown/" name="PDF に MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-xamlflow/" name="PDF に XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pdf-to-dotx/" name="PDF に DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}