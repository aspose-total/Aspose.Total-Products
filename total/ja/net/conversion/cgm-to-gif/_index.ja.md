---
title: CGMをGIFにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにCGMをGIFに変換する
url_ignore: /ja/net/conversion/cgm-to-gif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: GIF
otherformats: XAMLFLOW DOT MHTML PCL MARKDOWN RTF PS GIF OTT WORDML ODT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でCGMをGIFにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のGIFにCGMをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをGIFにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをGIFに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをGIF形式で保存し、GifをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してCGMファイルを(号化する" %}}
CGMをGIFに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用GIF-ファイルを作成" %}}
GIFを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをGIFに変換する：ユースケース" %}}
CGM (コンピュータグラフィックスメタファイル) を GIF (グラフィックス交換フォーマット) に変換する必要があります。これにより、視覚コンテンツの限界を掲げることができるので、さまざまな受け者と共有できる活発的な画像を作成することが可能になります。

CGM ファイルを GIF 形式に変換することで以下のような用途が実現されます：

**用途:**

* **ソーシャルメディアでのエンゲージメント**: ソーシャルメディアプラットフォームで共有できる GIF 作成に使用し、エンゲージメント レートを向上させたり、ブランド ビジュアルィティーを高めることができます。
* **ウェブサイトのインタラクション**: ホバー エフェクト、アンimatiosn、ローディング インディケーターなど、ウェブサイトでのインタラクティブなエクペリエンスを作成することができます。
* **マーケティング キャンペーン**: マーケティング キャンペーンのデータを可視化し、パフォーマンスを追跡し、戦略を最適化するために GIF に変換することができます。
* **教育コンテンツ**: 複雑な概念を生動で理解できる形式で表現するために GIF を使用し、教育材料やチュートリアルに適した内容を作成することができます。
* **EC コマーション**: プロダクト デモストレーション、カスタマー ベネフィットの強調、ショッピング エクペリエンスを向上させるために CGM ファイルを GIF に変換することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}