---
title: C＃APIを介してMDをXAMLにエクスポートする
description: MicrosoftWordを使用せずにMDをXAMLに変換する.NETAPI
url_ignore: /ja/net/conversion/md-to-xaml/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: XAML
otherformats: PPSX POTM OTP POT PPSM POWERPOINT PPS POTX PPT XAML PPTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してMDをXAMLにレンダリングする" h2="Microsoft<sup>＆reg;</sup> PowerPointを使用せずにWindows、macOS、およびLinux上のXAMLにMDをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
強力なファイル形式自動化APIのパッケージ[Aspose.Total for .NET](https://products.aspose.com/total/net/)を使用すると、2つの簡単な手順でMDをXAMLに簡単にレンダリングできます。 PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイル形式をPPTXに変換できます。その後、Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)を使用して、PPTXをXAMLに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをXAMLに変換する.NETAPI" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してMDをPPTXに変換します
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)クラスを使用してPPTXファイルをロードします
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)メソッドを使用してドキュメントをXAML形式で保存し、「Xaml」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由でMDファイルからXMPメタデータを取得する" %}}
MDをXAMLに変換する際、バッチ変換プロセスに優先順位を付けるために、追加のXMPメタデータ情報が必要になる場合があります。たとえば、作成日に基づいて変換ドキュメントを取得して並べ替え、それに応じてドキュメントを処理できます。 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイルのXMPメタデータにアクセスできます。 MDファイルのメタデータを取得するには、[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、入力MDファイルを開きます。その後、[Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)プロパティを使用してファイルのメタデータを取得できます。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="プログラムでMDファイルをXAMLに変換する：ユースケース" %}}
**マークダウンファイルをXAMLに変換する:ユーウィUIのフルパotentialを引き出す**

マークダウン（MD）ファイルは、コンテンツクリエーター、デベロッパー、デザイナーにとって不可欠なツールとなっています。しかし、ユーザーインターフェース（UI）の構築においては、XAML（Extensible Application Markup Language）は優れたフォーマットです。

マークダウンファイルをXAMLに変換することで、次のような利益があるためです:

**用途（Use Cases）:**

* **ユーザーインターフェースデザイン:** マークダウンファイルをXAMLに変換し、視覚的に魅力的な並び替え可能な、interactive UIコンポーネントを作成することができます。例えばボタン、ラベル、テキストボックスなど。
* **モバイルアプリ開発:** XAMLを使用して、画面サイズやオリエンテーションに応じて素早く適応するモバイルアプリを設計と構築することができます。
* **デスクトップアプリケーション開発:** マークダウンファイルをXAMLに変換し、カスタムUI要素、レイアウト、そしてアニメーションを含むデスクトップアプリケーションを作成することができます。
* **ウェブアプリケーション開発:** XAMLを使用して、データグリッド、チャート、地図などリッチなUIコンポーネントを含むウェブアプリケーションを設計と構築することができます。
* **アクセシビリティーオプティマイズ:** マークダウンファイルをXAMLに変換し、ユーザーに障害を抱える人々のためにARIA属性やキーボードナビゲーションを実装し、UIがアクセス可能な状態を作成することができます。

マークダウンファイルをXAMLに変換することで、ユーザーインターフェースのデザインキャパシティをフルに引き出し、ユーザーに魅力ある、interactive体験を提供することができるようになります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}