---
title: C＃APIを介してEPUBをPPTMにエクスポートする
description: MicrosoftWordを使用せずにEPUBをPPTMに変換する.NETAPI
url_ignore: /ja/net/conversion/epub-to-pptm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPTM
otherformats: PPS SWF POT OTP PPSM POTX PPSX PPT POTM PPTM POWERPOINT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してEPUBをPPTMにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のPPTMにEPUBをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でEPUBをPPTMに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをPPTMに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをPPTMに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してEPUBファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してEPUBをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをPPTM形式で保存し、「Pptm」をSaveFormatとして設定します
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
EPUBをPPTMに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイルのXMPメタデータにアクセスできます。 EPUBファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力EPUBファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用PPTMファイルを作成する" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、PPTMファイルを読み取り専用に設定できます。つまり、ユーザーは(プレゼンテーションを開いた後)読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pptm", SaveFormat.Pptm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEPUBファイルをPPTMに変換する：ユースケース" %}}
電子書（Electronic Publication）ファイルは、デジタルコンテンツを保存するために使用されます。しかし、インタラクティブプレゼンテーションを作成する際には、PowerPointの.pptm形式などは、観客を魅覚するために重要な形式です。

EPUBファイルをPPTM形式に変換する必要があります。これにより、プレゼンテーションの完全な可能性を引き出すことができます。以下の用途で役立ちます：

* **教育的なコンテンツを作成するためにEPUBファイルを変換します。**  
  - 学習レポート、チュートリアル、スタディーメァテリアルなど、インタラクティブな教育内容を制作するのに適しています。

* **企業でのトレーニングセッションを実施する際には、PPTM形式を使っています。**  
  - 社内研修、ワークショップ、従業員向けのプレゼンテーションを作成することができます。

* **会議資料としてEPUBファイルを変換します。**  
  - スライドショー、プレゼンテーション、ハンドアウトなど、完全な会議資料を制作するのに適しています。

* **オンラインコースの内容を作成する際には、PPTM形式を使用します。**  
  - レクチャースライド、課題、インタラクティブなテストなど、オンラインコースの全ての要素を含む資料を作成することができます。

* **マーケティングプレゼンテーションとしてEPUBファイルを変換します。**  
  - プロダクトデモ、売り上げ材料など、魅力あるマーケティングプレゼンテーションを作成するのに適しています。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}