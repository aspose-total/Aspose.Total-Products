---
title: CGMをFLATOPCにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにCGMをFLATOPCに変換する
url_ignore: /ja/net/conversion/cgm-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FLATOPC
otherformats: RTF DOT WORDML FLATOPC XAMLFLOW OTT PCL DOTX ODT MHTML MARKDOWN PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でCGMをFLATOPCにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のFLATOPCにCGMをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをFLATOPCにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをFLATOPCに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをFLATOPC形式で保存し、FlatopcをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してCGMファイルを復号化す(" %}}
CGMをFLATOPCに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用FLATOPC-ファイルを作成" %}}
FLATOPCを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.FlatOpc
document.Save("output.flatopc", SaveFormat.FlatOpc);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをFLATOPCに変換する：ユースケース" %}}
CGM（コンピュータグラフィックスメタファイル）形式のファイルは、ベクターグラフィックス情報を保存するために使用され、静的なグラフィックやイラストレーションを作成するのに適しています。しかし、ダイナミックなデータと仕事をする場合には、flatOPC 形式のファイルがリアルタイムのビジュアリゼ이션とコントロールに必要になるようになります。

CGM ファイルを flatOPC 形式に変換することは、自分のビジュアリゼイションやコントロール能力の完全な活用を可能にするために必要です。この変換により、次のような利益があるためには以下の点があります：

**使用事例：**

* **リアルタイムモニター**: CGM ファイルを flatOPC 形式に変換して、インタクティブなリアルタイムモニターボードを作成し、キーヵィーインデックス（KPIs）を追跡し、異常を警告することができます。
* **予測的分析**: flatOPC を使用して CGM データを分析し、トレンドを予測し、機器性能やメンテナンスについて知らせることができます。
* **オペ레이ターのトレーニングシミュレーション**: CGM ファイルを flatOPC 形式に変換して、イミーゼションしたトレーニングシミュレーションを作成し、オペレイターが機械を操作する方法を教え、トレーニングの効果を確認することができます。
* **リアルタイムデータのビジュアリゼ이션**: flatOPC を使用して、産業機器（ポンプ、バルブ、モーターなど）からのリアルタイムCGM データをビジュアリゼイションすることができます。
* **DCS システムとのインテグレーション**: CGM ファイルを flatOPC 形式に変換して、ディストリブユーティッド コントロール システム（DCS）とインテグレーションし、プロセス オペ레이션のシームレスなコントロールとモニタリングが可能になることが 있습니다。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}