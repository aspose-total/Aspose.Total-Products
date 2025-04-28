---
title: EPUBをPCLにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにEPUBをPCLに変換する
url_ignore: /ja/net/conversion/epub-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PCL
otherformats: DOTX ODT PS DOT RTF MHTML PCL OTT FLATOPC DOTM WORDML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEPUBをPCLにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のPCLにEPUBをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをPCLにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをPCLに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してEPUBファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してEPUBをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをPCL形式で保存し、PclをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してEPUBファイルを(号化する" %}}
EPUBをPCLに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してEPUBを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用PCL-ファイルを作成" %}}
PCLを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEPUBファイルをPCLに変換する：ユースケース" %}}
電子書籍（Ebooks）は、デジタルコンテンツを保存するためのフォーマットで、インタクティブなマルチメディアドキュメントを作成するのに適しています。しかし、プリンタブルオンディマンド（Print-on-Demand, POD）要件においては、プリントャブル コンテンツ ファイル（PCF）が必要となり、レイアウトやフォーマットを精确にコントロールするための重要なツールになります。

電子書籍をPCF形式に変換することは、自分のプリンタブルオンディマンド能力を最大限に活用するための必須の手段です。この変換により、次のような利益があるとします：

**利用事例：**

* **高品質な印刷**: エブックをPCF形式に変換し、プロフェッショナルな印刷物を作成することが可能になります。例えば、宣伝材料としてのflyerやブローシュールなど。
* **カスタムレイアウト**: PCFを用いて、印刷物のカスタムレイアウトを設計することができます。精确な位置付けとフォーマット設定が可能となり、誤差を最小限に抑え、効率性を向上させることができます。
* **ページレイアウトの精密制定**: エブックをPCF形式に変換し、ページレイアウトにおいてマージンやギャザーなど詳細な要素を精确にコントロールすることができるようになります。これによりエラーを減らし、効率性を向上させることができます。
* **具体的な業種や応用域に最適化**: PCFを用いて、特定の業種または応用域（例えば不動産、金融、医療など）に向けて印刷物を最適化することができるようになります。
* **高速なターンアラウンドタイム**: エブックをPCF形式に変換し、プリンタブルオンディマンドの生産において高速なターンアラウンドタイムを実現することができます。供給チェーンの管理も効率的に行うことができるようになります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}