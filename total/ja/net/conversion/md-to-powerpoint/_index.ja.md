---
title: C＃APIを介してMDをPOWERPOINTにエクスポートする
description: MicrosoftWordを使用せずにMDをPOWERPOINTに変換する.NETAPI
url_ignore: /ja/net/conversion/md-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: POWERPOINT
otherformats: PPSM POWERPOINT POT PPT SWF PPSX POTX OTP POTM PPTM XAML PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してMDをPOWERPOINTにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のPOWERPOINTにMDをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でMDをPOWERPOINTに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをPOWERPOINTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをPOWERPOINTに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してMDをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをPOWERPOINT形式で保存し、「Powerpoint」をSaveFormatとして設定します
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
MDをPOWERPOINTに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイルのXMPメタデータにアクセスできます。 MDファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力MDファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用POWERPOINTファイルを作成する" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、POWERPOINTファイルを読み取り専用に設定できます。つまり、ユーザーは(プレゼンテーションを開いた後)読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMDファイルをPOWERPOINTに変換する：ユースケース" %}}
マークダウン ファイルをパワー� ポイント形式に変換する必要があります。これにより、プレゼンテーション デザインの完全な可能性を引き出すことができます。この変換が可能にする機能は以下のような用途で役立つと考えられます：

**用途:**

* **ビジネス プレゼンテーション:** マークダウン ファイルを利用して、ビジネス関係者（管理者、利益関係者、顧客）に面白い ビジネス プレゼンテーション、インフォグラフィックス、スライドショーを作成することができます。
* **教育コンテンツの作成:** 複雑な概念、レクチャー、カースを容易く理解できる形式でプレゼンテーションを作成し、学習をよりアクセスibleにします。
* **個人プロジェクトとポートフォリオ:** マークダウン ファイルを利用して、スタイリッシュな 個人プロジェクト、ポートフォリオ、ブログを作成し、スキルと成就を示すことができます。
* **テクニカル ドキュメントとガイド:** ソフトウェア開発、エンジニアリングなどのテクニカル フィールドでinteractiveな テクニカル ドキュメント、チュートリアル、ガイドを作成することができます。
* **マーケティングとセールス マテリアル:** マーケティング プレゼンテーションやプロダクト デモ、キャッチィーな セールス マテリアルを作成し、観客の注意を引きつけます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}