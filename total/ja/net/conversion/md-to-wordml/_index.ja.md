---
title: MDをWORDMLにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにMDをWORDMLに変換する
url_ignore: /ja/net/conversion/md-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: WORDML
otherformats: DOTX PCL PS OTT FLATOPC MARKDOWN RTF ODT DOT XAMLFLOW MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でMDをWORDMLにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のWORDMLにMDをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをWORDMLにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをWORDMLに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してMDをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをWORDML形式で保存し、WordmlをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してMDファイルを復号化(る" %}}
MDをWORDMLに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してMDを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="プログラムでMDファイルをWORDMLに変換する：ユースケース" %}}
Markdown ファイル（MD）を WordML 形式に コンバージョンする必要があります。これにより、以下のような用途で 利用可能なります。

**用途:**

* **技術書作成とドキュメント作成:** Microsoft Office 要求に適した 技術ドキュメントやユーザーマニュアル、ガイドを 作成するために MD ファイルを WordML 形式に コンバージョンします。
* **ビジネスコミュニケーション:** ビジネスレポート、提案、プレゼンテーションなどのドキュメントを WordML 形式で 作成し、Microsoft Office アプリケーション で 利用可能にするために MD ファイルを コンバージョンします。
* **学術出版:** 学会論文や記事を WordML 形式で 提出するために MD ファイルを コンバージョンします。
* **マーケティングとセールス・マテリアル:** プロモーション情報を含む ブロシャー、フライヤー、セールスシートなどのマーケティングマテリアルを WordML 形式で 作成するために MD ファイルを コンバージョンします。
* **オンライン学習コンテンツの開発:** Microsoft Office アプリケーション で 显に提出可能な 教育コンテンツや カースワード材を WordML 形式で 作成するために MD ファイルを コンバージョンします。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}