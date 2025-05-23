---
title: PSをWORDMLにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにPSをWORDMLに変換する
url_ignore: /ja/net/conversion/ps-to-wordml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: WORDML
otherformats: FLATOPC PCL DOTX ODT DOTM MARKDOWN XAMLFLOW WORDML OTT DOT RTF MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でPSをWORDMLにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のWORDMLにPSをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、PSファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをWORDMLにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PSをWORDMLに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してPSファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してPSをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをWORDML形式で保存し、WordmlをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してPSファイルを復号化(る" %}}
PSをWORDMLに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してPSを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用WORDML-ファイルを作成" %}}
WORDMLを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでPSファイルをWORDMLに変換する：ユースケース" %}}
PS (ポータブル ドキュメント フォーマット、PDF) ファイルは、固定レイアウトのドキュメントを保存するために使用され、プロフェッショナルな見た目を持つレポート、ブログやプレゼンテーションを作成するための理想的な形式です。しかし、データ ドライブド コンテンツと仕事をする場合には、XMLベースのワードマークアップ ランゲージ（WordML）が必要となり、データ ビジュアリзаーションや分析に不可欠なります。

PS ファイルをワードマークアップ ランゲージ形式へ変換することが求められます。これにより、以下のような利益があるためです：

**用途:**

* **データ ドライブド レポート:** PS ファイルをインタクティブなレポートやダッシュボード、ビジュアリゼーションを作成し、ステークホルダーに提供することで、より良い決策-making を支援します。
* **コンテンツ マネージメント システム（CMS）との イン테グレーション:** ワードマークアップ ランゲージを用いて、PS ベースのコンテンツを CMS プラットフォームに イン테グレーションし、パブリッシング プロセスをスムーズ化します。
* **アクセスिबリティー向上:** PS ファイルをワードマークアップ ランゲージ形式へ変換することで、障碍者との アクセスिबリティーを向上させることができます。ワードマークアップ ランゲージには内蔵された アクセスिबリティー機能があります。
* **データ ビジュアリзаーションと 分析:** ワードマークアップ ランゲージを用いて、PS ドキュメント内で データを ビジュアリゼーションし、分析することで、深い見込みとより良い決策-making を可能にします。
* **レガシー システムへの マイグレーション:** PS ファイルをレガシー システムから 新しい プラットフォームへ マイグレーションすることができるようにし、ワードマークアップ ランゲージの コンパティビリティーと フレキシビリティーを活用します。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}