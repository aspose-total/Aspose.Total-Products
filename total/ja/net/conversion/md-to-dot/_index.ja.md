---
title: MDをDOTにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにMDをDOTに変換する
url_ignore: /ja/net/conversion/md-to-dot/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOT
otherformats: FLATOPC WORDML PCL DOT DOTM ODT RTF MHTML OTT MARKDOWN XAMLFLOW DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でMDをDOTにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のDOTにMDをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをDOTにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをDOTに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してMDをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOT形式で保存し、DotをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してMDファイルを(号化する" %}}
MDをDOTに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してMDを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用DOT-ファイルを作成" %}}
DOTを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMDファイルをDOTに変換する：ユースケース" %}}
**変換ケース:** マークダウン (Markdown) ファイルは、テキストベースの情報を保存するのに適した形式で、シンプルなドキュメント作成やコンテンツ作成に最適しています。しかし、複雑なフォーマットとレイアウト要求がある場合には、DOT (ダイアグラム インターチェンジng ファイル フォーマット) ファイルが視覚的な表現に必要となるため、使用されるようになります。

マークダウン ファイルを DOT 形式に変換することは、自分のビジュアル表現能力を完全に活用するための必要な操作です。この変換により、次のような利益があると言います:

**用途:**

* **技術ドキュメント:** 技術的なドキュメントを作成するために、マークダウン ファイルを DOT 形式に変換し、インタラクティブなダイアグラムやフローチャートを作成することができるため、理解とナビゲーションが容易になります。
* **ビジネスプロセスマイニング:** 複雑なビジネス プロ세スを視覚的に表現するために、DOT を使用し、インタラクティブでダイナミックなモデルの作成と分析、最適化が可能になります。
* **ソフトウェア開発とアーキテクチャ:** ソフトウェアの詳細なアーキテクチャー ダイアグラムや UML クラス図、システム アーキテクチャー モデルを作成するために、マークダウン ファイルを DOT 形式に変換し、プロジェクト計画と実行が向上します。
* **教育とトレーニングマテリアル:** インタラクティブなチュートリアル、ガイド、教材を作成するために、DOT を使用し、複雑な情報を学習者にアクセスしやすく、関心を持たせます。
* **研究と学術プレゼンテーション:** 研究の結果やデータを清潔に表現するため、マークダウン ファイルを DOT 形式に変換し、視覚的に吸引的な学術ポスター、レポートを作成することができます。

マークダウン ファイルを DOT 形式に変換することで、自分のビジュアル表現能力を完全に活用し、コミュニケーション、協働作業、そして判断を向上させるためのインタラクティブでダイナミックなダイアグラムを作成することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}