---
title: C＃APIを介してCGMをPOWERPOINTにエクスポートする
description: MicrosoftWordを使用せずにCGMをPOWERPOINTに変換する.NETAPI
url_ignore: /ja/net/conversion/cgm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POWERPOINT
otherformats: OTP PPSM PPS XAML PPSX PPT POTX PPTM POWERPOINT POT POTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してCGMをPOWERPOINTにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のPOWERPOINTにCGMをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でCGMをPOWERPOINTに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをPOWERPOINTに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをPOWERPOINTに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをPOWERPOINT形式で保存し、「Powerpoint」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でCGMファイルからXMPメタデータを取得する" %}}
CGMをPOWERPOINTに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイルのXMPメタデータにアクセスできます。 CGMファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力CGMファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをPOWERPOINTに変換する：ユースケース" %}}
CGM（コンピュータグラフィックスメタファイル）形式のファイルは、ベクター・グラフィックスの情報を保存するために使用され、静的なグラフィックスやイラストレーションを作成するのに適しています。しかし、ダイナミックなデータと働く場面では、パワーユージングのようなプレゼンテーションツールが必要になります。

CGM形式のファイルをパワーユージング形式に変換することが求められます。これにより、次のような用途で役立つようにします：

**用途：**

* **企業向けプレゼンテーション**: CGM ファイルを利用して、面白い企業プレゼンテーションを作成し、複雑なデータの洞察を伝達し、株主や関係者に共有することができます。
* **トレーニングマテリアル開発**: パワーユージングでトレーニングコンテンツを視覚化し、リアルワールドのシミュレーションを行うことや、インタラクティブな学習体験を提供することができます。
* **マーケティングマテリアル作成**: CGM ファイルを利用して、目を引くようなビジュアルに設計されたマーケティングマテリアルを作成し、注意力を引きつけ、関心を高めることができます。
* **科学技術向けプレゼンテーション**: パワーユージングで複雑なデータを視覚化し、研究の結論を明瞭に伝達することができるようにします。
* **オンライン学習コース開発**: CGM ファイルを利用して、ユーザーに完全に浸没したオンライン学習コースを作成し、アニメーションやインタラクションを活用し、学習者の関心を高めることができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}