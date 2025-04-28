---
title: CGMをXAMLFLOWにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにCGMをXAMLFLOWに変換する
url_ignore: /ja/net/conversion/cgm-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XAMLFLOW
otherformats: MARKDOWN DOTX XAMLFLOW OTT ODT DOTM DOT WORDML PCL MHTML FLATOPC RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でCGMをXAMLFLOWにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のXAMLFLOWにCGMをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをXAMLFLOWにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをXAMLFLOWに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをXAMLFLOW形式で保存し、XamlflowをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.xamlflow", SaveFormat.Xamlflow);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してCGMファイルを復号化する" %}}
CGMをXAMLFLOWに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用XAMLFLOW-ファイルを作成" %}}
XAMLFLOWを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xamlflow", SaveFormat.Xamlflow);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをXAMLFLOWに変換する：ユースケース" %}}
**CGM (Computer Graphics Metafile) ファイルの XAMLFlowへの変換**

CGMファイルは、ベクタグラフィックス情報を保存するために使用され、静的なグラフィックやイラストレーションを作成するのに適しています。しかし、ダイナミックなデータに対応する必要がある場合、XAMLFlowはデータ可視化と分析に不可欠なツールとなります。

CGMファイルをXAMLFlow形式に変換することは、データ可視化や分析の可能性を引き出すために必須です。この変換により、以下のようなことが可能になります：

**用途：**

* **インタラクティブプロトタイプ**: CGMファイルを用いたインタラクティブプロトタイプの作成、ユーザー体験のシミュレーション、デザインコンセプトの検証を行い、XAMLFlowで実現します。
* **データドライブンテーリング**: 複雑なデータセット（例：3Dモデル、シミュレーション結果、実験データ）をXAMLFlowで可視化し、聆取者とのエンゲージングなストーリーテリングを行います。
* **リアルタイムフィードバックループ**: CGMファイルを用いたリアルタイムフィードバックループの作成で、XAMLFlowで即時の調整と最適化が可能になります。
* **メディアプレゼンテーション**: CGMファイルをメディア要素（例：ビデオ、音声）と組み合わせて、XAMLFlowでエンゲージングなプレゼンテーションや展示物を作成します。
* **共同設計と開発**: CGMファイルを用いた共同設計と開発を可能にし、XAMLFlowで複数の利害関係者がプロジェクトに共同で働きかけます。

CGMファイルをXAMLFlowに変換することで、データ可視化、分析、そして協働作成にとって無限の可能性が開かれます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}