---
title: C＃APIを介してEPUBをPPSにエクスポートする
description: MicrosoftWordを使用せずにEPUBをPPSに変換する.NETAPI
url_ignore: /ja/net/conversion/epub-to-pps/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPSX XAML PPT PPTM POTM POTX SWF PPS OTP POT PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してEPUBをPPSにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のPPSにEPUBをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でEPUBをPPSに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをPPSに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをPPSに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してEPUBファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してEPUBをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをPPS形式で保存し、「Pps」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でEPUBファイルからXMPメタデータを取得する" %}}
EPUBをPPSに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイルのXMPメタデータにアクセスできます。 EPUBファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力EPUBファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用PPSファイルを作成する" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、PPSファイルを読み取り専用に設定できます。つまり、ユーザーは(プレゼンテーションを開いた後)読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEPUBファイルをPPSに変換する：ユースケース" %}}
EPUB（電子出版形式）ファイルは、デジタルコンテンツを保存するために使用され、理想的に電子書籍や記事など書籍物の作成と配布に適しています。しかし、プレゼンテーションデータとの取り組みにおいて、パワーポイントファイル（PPS）は制作するための重要なツールとなり、面白いスライドショーとプレゼンテーションを作成するのに不可欠です。

EPUB ファイルを PPS 形式に変換することが必要となります。これにより、プレゼンテーションの可能性を最大限活用することが可能になります。以下の用途が実現されます：

**用途:**

* **企業向けコミュニケーション**: 年次報告書、会社ニュース、製品ランチングなど面白い企業向けコミュニケーションを作成するためにEPUB ファイルを PPS に変換します。
* **学術研究プレゼンテーション**: 研究成果のプレゼンテーションを行うため、または同僚と協力して知識を共有するためにPPS を使用します。
* **eラーニングコンテンツの作成**: インタラクティブなeラーニングマテリアルやシミュレーション、チュートリアルを作成するためにEPUB ファイルを PPS に変換します。
* **デジタルパブリッシング**: 各種プラットフォームで配布するため、PPS を使用して電子書籍、雑誌、新聞などデジタルコンテンツを出版します。
* **イベントプレゼンテーション**: イベントや会議、ウェブセミナーでのダイナミックなプレゼンテーションを作成するためにEPUB ファイルを PPS に変換します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}