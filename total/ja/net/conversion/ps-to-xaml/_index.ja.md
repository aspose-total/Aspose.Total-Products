---
title: C＃APIを介してPSをXAMLにエクスポートする
description: MicrosoftWordを使用せずにPSをXAMLに変換する.NETAPI
url_ignore: /ja/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してPSをXAMLにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のXAMLにPSをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でPSをXAMLに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、PSファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをXAMLに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PSをXAMLに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してPSファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してPSをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをXAML形式で保存し、「Xaml」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でPSファイルからXMPメタデータを取得する" %}}
PSをXAMLに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、PSファイルのXMPメタデータにアクセスできます。 PSファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力PSファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NETを介して読み取り専用XAMLファイルを作成する" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/)APIを使用すると、変換アプリケーションの機能をさらに強化できます。機能の1つは、セキュリティを強化するために読み取り専用の出力ファイルを作成することです。 APIを使用すると、XAMLファイルを読み取り専用に設定できます。つまり、ユーザーは(プレゼンテーションを開いた後)読み取り専用の推奨事項を参照できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでPSファイルをXAMLに変換する：ユースケース" %}}
PS (ポータブル ドキュメント フォーマット) ファイルは、ベクター グラフィックス情報を保存するために使用され、静的なグラフィック、ロゴ、イラストレーションなどを作成するのに適しています。しかし、ダイナミックなデータと働く場合には、XAML (エクステンシブル アプリケーション マークアップ ランゲージ) がユーザー インターフェースやアプリケーションのビルディング에必要になります。

PS ファイルを XAML 形式に変換することが求められます。これにより、your application development capabilities を完全に活用することが可能になります。この変換が許可することは：

**Use Cases:**

*   **モバイル アプリケーション開発**: PS ファイルを XAML で変換し、直感的なユーザー インターフェースをもつネイティブ モバイル アプリを作成することができます。XAML を活用して、ユーザー エクスペリエンスに隙がなくなるようにします。
*   **デスクトップ アプリケーション開発**: XAML を使って、データ バインディング、アンimatiosn、テンプレートなどの強みところを活用して、レスポジィブでスケーラブルなデスクトップ アプリを作成することができます。
*   **UI コンポーネント ライブラリ**: PS ファイルを XAML で変換し、再利用可能な UI コンポーネント（ボタン、テキスト フィールド、メニューなど）を作成することができます。XAML を使って、高効率でメンテナブルなデザインができるようにします。
*   **3D グラフィックスとアニメーション**: XAML を活用して、your アプリケーションに 3D グラフィックスとアニメーションを加えることができます。ベクター グラフィックスの力とマークアップ言語の柔軟性を組み合わせています。
*   **アクセスिबリティーとカスタマイゼーション**: PS ファイルを XAML で変換し、 アクセスिबリティーとカスタマイゼーションが可能な UI 要素を作成することができます。your アプリケーションが多様なユーザー ニーズと プレファレンスに応じて作り出すようにします。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}