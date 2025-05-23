---
title: C＃APIを介してEPUBをOTPにエクスポートする
description: MicrosoftWordを使用せずにEPUBをOTPに変換する.NETAPI
url_ignore: /ja/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してEPUBをOTPにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のOTPにEPUBをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でEPUBをOTPに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをOTPに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをOTPに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してEPUBファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してEPUBをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをOTP形式で保存し、「Otp」をSaveFormatとして設定します
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
EPUBをOTPに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイルのXMPメタデータにアクセスできます。 EPUBファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力EPUBファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用OTPファイルを作成する" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、OTPファイルを読み取り専用に設定できます。つまり、ユーザーは(プレゼンテーションを開いた後)読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEPUBファイルをOTPに変換する：ユースケース" %}}
電子書（E-book）ファイルは、デジタルコンテンツを保存するために使用され、ダイナミックなコンテンツやインタラクティブなエクスペリエンスを作成するのに適しています。しかし、オフラインデータと仕事をする場合、テキストファイルは長期的な保存とアーカイヴ作成の目的で欠かせないものです。

電子書ファイルをオフラインテキストファイルに変換する必要があります。これにより、アンリミテッドのアーカイヴやリブラリーの機能を完全に活用することが可能になります。この変換が可能な理由は以下の通りです：

**使用事例:**

* **デジタルパreservation**: エBOOKファイルを永続的なアーカイヴを作成し、デジタルコンテンツが長期にわたるアクセス可能性を保つことができるようにします。
* **オフラインリーディングとシェアリング**: オフラインテキストファイルを使用して、インターネット接続を必要とせずにデジタルコンテンツを配布することができます。これは、インターネットが利用できない地域やWi-Fiが unavailableな状況で役立つします。
* **リブラリーの管理と組織化**: エBOOKファイルをオフラインテキストファイルに変換し、テキストデータの収集、検索、カテゴライゼーション、そして情報取得を容易くすることができるようにします。
* **デジタルアーカイヴと復旧**: オフラインテキストファイルを使用して、損傷したコンテンツを保存し、未来世代に残すことができるようにします。これは、重要な情報を失わないために役立つします。
* **オフラインコンテンツの作成と編集**: エBOOKファイルをオフラインテキストファイルに変換し、インターネット接続が必要ではなくても編集可能な内容を作成することができるようにします。作者、作家、出版社などネットワーク接続が制限された環境で働く者向けに適しています。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}