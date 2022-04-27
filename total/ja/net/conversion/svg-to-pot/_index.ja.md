---
title: C＃APIを介してSVGをPOTにエクスポートする
description: MicrosoftWordを使用せずにSVGをPOTに変換する.NETAPI
url: /ja/net/conversion/svg-to-pot/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: POT
otherformats: POTX SWF OTP POT POTM PPS POWERPOINT PPSX PPTM XAML PPSM PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してSVGをPOTにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のPOTにSVGをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET]（https://products.aspose.com/total/net/）を使用すると、2つの簡単な手順でSVGをPOTに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET]（https://products.aspose.com/pdf/net/）を使用すると、SVGファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET]（https://products.aspose.com/slides/net/）を使用して、PPTXをPOTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SVGをPOTに変換する.NETAPI" %}}
1. [ドキュメント]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）クラスを使用してSVGファイルを開きます
2. [保存]（https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5）メソッドを使用してSVGをPPTXに変換します
3. [プレゼンテーション]（https://apireference.aspose.com/slides/net/aspose.slides/presentation）クラスを使用してPPTXファイルをロードします
4. [保存]（https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5）メソッドを使用してドキュメントをPOT形式で保存し、「Pot」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード]（https://downloads.aspose.com/total/net）からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.svg");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でSVGファイルからXMPメタデータを取得する" %}}
SVGをPOTに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET]（https://products.aspose.com/pdf/net/）を使用すると、SVGファイルのXMPメタデータにアクセスできます。 SVGファイルのメタデータを取得するには、[ドキュメント]（https://apireference.aspose.com/pdf/net/aspose.pdf/document）オブジェクトを作成し、入力SVGファイルを開きます。その後、[Metadata]（https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata）プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.svg");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用POTファイルを作成する" %}}
[Aspose.Slides for .NET]（https://products.aspose.com/slides/net/）APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、POTファイルを読み取り専用に設定できます。つまり、ユーザーは（プレゼンテーションを開いた後）読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-pot/" name="SVG に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-ppsx/" name="SVG に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-swf/" name="SVG に SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-powerpoint/" name="SVG に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-otp/" name="SVG に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-potm/" name="SVG に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-ppt/" name="SVG に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-pps/" name="SVG に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-potx/" name="SVG に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-xaml/" name="SVG に XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-ppsm/" name="SVG に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/svg-to-pptm/" name="SVG に PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}