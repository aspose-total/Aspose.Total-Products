---
title: C＃APIを介してMDをSWFにエクスポートする
description: MicrosoftWordを使用せずにMDをSWFに変換する.NETAPI
url_ignore: /ja/net/conversion/md-to-swf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SWF
otherformats: PPS PPSM PPSX OTP SWF POT PPTM POTX XAML POWERPOINT PPT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してMDをSWFにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のSWFにMDをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でMDをSWFに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをSWFに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをSWFに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してMDをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをSWF形式で保存し、「Swf」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMDファイルからXMPメタデータを取得する" %}}
MDをSWFに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイルのXMPメタデータにアクセスできます。 MDファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力MDファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用SWFファイルを作成する" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、SWFファイルを読み取り専用に設定できます。つまり、ユーザーは(プレゼンテーションを開いた後)読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMDファイルをSWFに変換する：ユースケース" %}}
マークダウン ファイルを SWF 形式に コンバージョンすることは、プレゼンテーションの フル ポテンシャル을 解放するのに 必要な 事です。この コンバージョンにより、次のような 用途에서 利用できるようになります。

**用途:**

* **企業 プレゼンテーション:** マークダウン ファイルを SWF 形式に コンバージョンし、魅力ある且インタラクティブなプレゼンテーションを作成することができます。これは、企業の イベント、ミーティング、コンファレンスなどで 利用できるものです。
* **e-ラーニング コンテンツの 作成:** SWF 形式を 활용して、-immersive な e-ラーニング モジュール、シミュレーション、インタクティブな タートリアルを作成し、知識の保持とスキルの向上을 增進することができます。
* **モバイル アプリ開発:** マークダウン ファイルを SWF 形式に コンバージョンし、モバイル アプリに インタラクティブな 要素、アンimatiosn、ダイナミックな コンテンツ를 포함한 앱을 만들 수 있습니다。
* **ゲーム 및 インタラクティ브 エクスペリエンス:** SWF 形式を 활용して、2D および 3D 環境で インマーシ브な ゲームや エクスペリエンスを作成し、プレイヤーが 탐索できるようにすることができます。
* **デジタル パブリッシング 및 マガジン:** マークダウン ファイルを SWF 形式に コンバージョンし、アンimatiosn、サウンド エフェクト、モーション グラフィックスと 함께蘇る インタラクティブな デジタル マガジン、コミック、グラフィック ノベルを作成することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}