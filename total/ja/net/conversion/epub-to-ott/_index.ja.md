---
title: EPUBをOTTにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにEPUBをOTTに変換する
url_ignore: /ja/net/conversion/epub-to-ott/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTT
otherformats: OTT DOT XAMLFLOW PCL MHTML DOTM WORDML FLATOPC DOTX MARKDOWN ODT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でEPUBをOTTにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のOTTにEPUBをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、EPUBファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをOTTにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUBをOTTに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してEPUBファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してEPUBをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをOTT形式で保存し、OttをSaveFormatとして設定します
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
EPUBをOTTに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してEPUBを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用OTT-ファイルを作成" %}}
OTTを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでEPUBファイルをOTTに変換する：ユースケース" %}}
電子書（EPUB）ファイルは、デジタルコンテンツを保存するために使用され、読みやすいドキュメントやパブリケーションを作成するのに適しています。しかし、メディア内容と関わる場合には、HTML ファイルが作り出すインテラクティブな体験を実現する必要があります。

電子書ファイルをHTML形式に変換することは、インタラクティブなコンテンツの完全な可能性を引き出し、以下のような利益があるためです：

**用途（Use Cases):**

* **デジタル出版**: インタラクティブな電子書籍や雑誌、新聞をオンラインで簡単に共有できるようにするために、電子書ファイルをHTML形式に変換します。
* **メディア芸術のストーリーテリング**: イメージ、ビデオ、オーディオ、アンیمーションを含む多媒体ストーリーを生まれ変わらせるために、HTML を活用します。
* **eラーニングコンテンツ**: クイズ、ゲーム、シミュレーションなどのインタラクティブなeラーニングマテリアルを作成するために、電子書ファイルをHTML 形式に変換します。这些材料は容易に更新と共有が可能です。
* **ウェブパブリッシング**: HTML を使用してウェブサイトやブログにデジタルコンテンツを公開し、読者やビューヤー向けにエンゲージングなオンライン体験を作成します。
* **アクセス性向上**: 電子書ファイルをHTML 形式に変換することで、障碍を有するユーザーも利用できるようなアクセス可能なデジタルコンテンツを作成し、助適技術を活用することができます。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}