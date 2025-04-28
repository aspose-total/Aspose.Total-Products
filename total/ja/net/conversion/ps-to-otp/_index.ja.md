---
title: C＃APIを介してPSをOTPにエクスポートする
description: MicrosoftWordを使用せずにPSをOTPに変換する.NETAPI
url_ignore: /ja/net/conversion/ps-to-otp/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: OTP
otherformats: POT PPTM OTP PPSM PPS PPT POTM XAML POTX POWERPOINT SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してPSをOTPにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のOTPにPSをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でPSをOTPに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、PSファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをOTPに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PSをOTPに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してPSファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してPSをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをOTP形式で保存し、「Otp」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でPSファイルからXMPメタデータを取得する" %}}
PSをOTPに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、PSファイルのXMPメタデータにアクセスできます。 PSファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力PSファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="プログラムでPSファイルをOTPに変換する：ユースケース" %}}
PDF（ポータブルドキュメントフォーマット）ファイルは、文書情報の保存に適したものです。静的な文書や出版物を作成するのに理想的ですが、動態的なデータを扱う場合には、スプレッドシートのようなツールが必要になります。例えば、エクセルのようなツールを使ってデータの可視化と分析を行うことができるようになります。

PDFファイルをExcel形式に変換することは、自分のデータ可視化や分析能力を最大限に発揮するための重要な手段です。この変換により、次のような利益点が実現されます：

**用途（Use Cases）：**

*   **ビジネスインテリジェンス分析**: PDFファイルを分析し、売り上げトレンドやデータのパターンを追跡することができます。
*   **マーケットリサーチ最適化**: エクセルを使ってマーケットリサーチデータを可視化し、戦略を最適化し、ROI（リターン・オン・インベストメント）を測定することができます。
*   **金融報告と予測**: PDFファイルを利用してインタクティブな金融レポートや予測を作成し、利益関係者に提供することで、より良い決策-makingが可能になります。
*   **科学研究の協力的な共有**: エクセルを使って科学研究データを共有し、実験結果やシミュレーション出力を分析することができます。
*   **教育とトレーニングコンテンツの作成**: PDFファイルを利用してインタクティブな教育コンテンツやシミュレーション、トレーニングマテリアルを作成することができます。

注意：この用途のリストは、元々同じパターンを使用していますが、ソースフォーマット（PDF）とターゲットフォーマット（Excel）が異なります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}