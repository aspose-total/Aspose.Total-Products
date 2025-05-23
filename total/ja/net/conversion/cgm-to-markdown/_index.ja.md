---
title: CGMをMARKDOWNにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにCGMをMARKDOWNに変換する
url_ignore: /ja/net/conversion/cgm-to-markdown/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MARKDOWN
otherformats: MARKDOWN WORDML DOTX DOT DOTM XAMLFLOW FLATOPC ODT OTT RTF PCL MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でCGMをMARKDOWNにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のMARKDOWNにCGMをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをMARKDOWNにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをMARKDOWNに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをMARKDOWN形式で保存し、MarkdownをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してCGMファイルを復号化する" %}}
CGMをMARKDOWNに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用MARKDOWN-ファイルを作成" %}}
MARKDOWNを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.markdown", SaveFormat.Markdown);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをMARKDOWNに変換する：ユースケース" %}}
CGM（コンピュータ・グラフィックス・メタファイル）形式は、ベクター・グラフィックスの情報を保存するために使用され、静的なグラフィックやイラストレーションを作成するのに適しています。しかし、ダイナミックなデータと働く場合には、スプレッドシートのようなツール（例：Excel）が必要となり、データの可視化や分析に役立ちます。

CGM ファイルをマークダウン形式に変換することが求められます。これにより、データのプレゼンテーションやドキュメンテーションの可能性を完全に活用することが可能になります。この変換が実現できる利益は次のような点です：

**使用例：**

* **静的なグラフィックのドキュメンテーション**：CGM ファイルをマークダウン形式に変換して、詳細な、interactive なドキュメンテーションを作成し、開発者、デザイナー、利益関係者らが協力することを容易にします。
* **データのストーリーテリング**：マークダウンを使用して複雑なデータの洞察を視覚的に表現し、鍵となる事実やトレンド、パターンを伝えるためのエンゲージングなストーリーを作成することが可能です。
* **デジタル・アセット・マネージメント**：CGM ファイルをマークダウン形式に変換して、ベクター・グラフィックス、ロゴ、アイコンなどのデジタル・アセットを管理する中央枢として利用し、使用状況、更新、修正などを容易に追跡することができます。
* **科学的なライティングや研究**：マークダウンを使用して複雑な科学的研究の結果を簡単に表現し、3D モデル、シミュレーション 結果、実験データなどを理解やすい形式で発表することが可能です。
* **interactive なウェブコンテンツの作成**：CGM ファイルをマークダウン形式に変換して、アンimat ions、シミュレーション、ビジュアル化などinteractiveなウェブコンテンツを作成し、ユーザーを引き込むことができるだけでなく、複雑な情報の伝達や理解促進にも役立ちます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}