---
title: PSをMARKDOWNにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにPSをMARKDOWNに変換する
url_ignore: /ja/net/conversion/ps-to-markdown/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MARKDOWN
otherformats: WORDML DOT XAMLFLOW OTT RTF MHTML ODT PCL FLATOPC DOTM MARKDOWN DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でPSをMARKDOWNにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のMARKDOWNにPSをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、PSファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをMARKDOWNにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PSをMARKDOWNに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してPSファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してPSをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをMARKDOWN形式で保存し、MarkdownをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してPSファイルを復号化する" %}}
PSをMARKDOWNに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してPSを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="プログラムでPSファイルをMARKDOWNに変換する：ユースケース" %}}
**PS Format (ポータブルドキュメントフォーマット) ファイルは、レイヤー化されたグラフィックス情報を保存するために使用され、静的なイメージやドキュメントを作成するのに適しています。しかし、ダイナミックなデータと仕事をする場合には、マークダウンが必要となり、ドキュメントとプレゼンテーションのための説明や発表に最適になります。

PS ファイルをマークダウン形式に変換することが必要となります。これにより、以下のような利点を実現できます：

**用途:**

* **ドキュメンテーションとブログ作成**: 高品質のイメージとフォーマットが含まれるインタクティ브なドキュメントやブログ記事、レポートを作成することが可能になります。
* **プレゼンテーションとスライドショー**: テキストベースのフォーマットを活用して、引人入りのプレゼンテーションやスライドショー、トークを作成することができます。
* **イメージ最適化と圧縮**: PS ファイルをウェブ向きに最適化し、ファイルサイズを小さくし、ページロード時間を短めます。これにより、ユーザー体験が向上します。
* **コンテンツマネージメントとパブリッシュ**: マークダウンを使用して、多くのプラットフォーム（ウェブサイト、ブログ、ソーシャルメディアなど）で共有できるコンテンツを管理し、パブリッシュすることが可能になります。
* **アクセシビリティーとインクルスив・デザイン**: PS ファイルをマークダウン形式に変換し、より広範な層のユーザーにアクセスしやすくなるだけでなく、インクルスिव・デザインの基準に適合するドキュメントやプレゼンテーションを作成することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}