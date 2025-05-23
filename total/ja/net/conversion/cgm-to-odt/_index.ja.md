---
title: CGMをODTにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにCGMをODTに変換する
url_ignore: /ja/net/conversion/cgm-to-odt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODT
otherformats: ODT MARKDOWN RTF PS XAMLFLOW DOTM PCL WORDML FLATOPC MHTML DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でCGMをODTにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のODTにCGMをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、CGMファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをODTにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGMをODTに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してCGMファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してCGMをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをODT形式で保存し、OdtをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してCGMファイルを(号化する" %}}
CGMをODTに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してCGMを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用ODT-ファイルを作成" %}}
ODTを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでCGMファイルをODTに変換する：ユースケース" %}}
CGM ファイルを ODT 形式に 导入することは、 あなたのドキュメント ビジュアライゼーション および 分析 能力を 最大限 活用するための 必要な 作行です。

CGM ファイルを ODT 形式に 导入することで、 次のような 利用 事例が 行えるようになります：

**利用 事例:**

* **ドキュメント デザイン および 編集:** CGM ファイルを ODT 形式に 导入し、 インタラクティブな ドキュメント デザイン を 作成し、 テキスト レイアウト을 編集し、 フォーマット コンセプトを 検証することができます。
* **ビジネス レポート および ダッシュボード:** ODT を 利用して ビジネス データを ビジュアライゼーションし、 売り チャート、 クラスターマー ビハーフ、 市場 分析など を 表示することができます。
* **テクニカル ライティング および ドキュメンテ이션:** CGM ファイルを ODT 形式に 导入し、 インタラクティブな ドキュメント을 作成하고、 コンテンツ ライブラリ를 管理し、 バージョン 히スト리를 チェックすることができます。
* **E-ラーニング 開発:** ODT を 利用して インタラクティブな E-レーニング マテリアルを開発し、 ユーザー エクスペリエンス을 シミュレートし、 学習 결과를 検証することができます。
* **データ レポート および ビジュアライゼーション:** CGM ファイルを ODT 形式に 导入し、 データ ドライブンな レポート、 ダッシュボード、 ヴィジュアル을 作成하고、 ステークホルダー에게 제공し、Better Decision-Making を 실現することができます。

CGM ファイルを ODT 形式に 导入することで、あなたのドキュメント ビジュアライゼーション および 分析 能력을 最大限 活用することが 됩니다。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}