---
title: MDをDOTMにエクスポートするためのC＃API
description: MicrosoftWordを使用せずにMDをDOTMに変換する
url_ignore: /ja/net/conversion/md-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOTM
otherformats: FLATOPC ODT WORDML OTT DOT RTF PS MHTML MARKDOWN DOTX DOTM XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET経由でMDをDOTMにレンダリングする" h2="MicrosoftWordを使用せずにWindows、macOS、およびLinux上のDOTMにMDをエクスポートするための.NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)は、.NETアプリケーション内にドキュメント操作および変換機能を追加するための強力なAPIです。高度なPDF処理API[Aspose.PDFfor .NET](https://products.aspose.com/pdf/net/)を使用すると、MDファイル形式をDOCに変換できます。その後、強力なドキュメント処理API [Aspose.Words for .NET](https://products.aspose.com/words/net/)を使用して、DOCをDOTMにレンダリングできます。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをDOTMに変換するC＃API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)クラスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)メソッドを使用してMDをドキュメントに変換します
3. Aspose.Wordsの[Document](https://reference.aspose.com/words/net/aspose.words/document)クラスを使用してDocファイルをロードします
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)メソッドを使用してドキュメントをDOTM形式で保存し、DotmをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/net)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET経由で所有者パスワードを使用してMDファイルを復(化する" %}}
MDをDOTMに変換する前に、ドキュメントを復号化する場合は、APIを使用して復号化できます。 PDFファイルを復号化するには、最初に[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)オブジェクトを作成し、所有者のパスワードを使用してMDを開く必要があります。その後、Documentオブジェクトの[Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt)メソッドを呼び出す必要があります。最後に、DocumentオブジェクトのSaveメソッドを使用して更新されたファイルを保存します。  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
((
{{% blocks/products/pf/feature-page-section  h2=".NET経由で読み取り専用DOTM-ファイルを作成" %}}
DOTMを編集から保護し、他の人がドキュメント内の機密情報を編集するのを防ぐために、APIを使用してドキュメントの保護を設定することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可することができます。これは、[Aspose.Words for .NET](https://products.aspose.com/words/net/)APIを使用して実行できます。 [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)列挙型パラメーターを使用して、コンテンツを制限する方法を制御できます。次のコード行を使用して、ドキュメントを読み取り専用に設定できます。 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="プログラムでMDファイルをDOTMに変換する：ユースケース" %}}
マークダウン（MD）ファイルをマイクロソフト オフィス ドキュメント マーケット ランゲージ（.dotm）ファイルに変換する必要があります。これにより、ドキュメント エディット capabilitiesを最大限活用することが可能になります。この変換が許可する機能の詳細は以下です。

**使用方法:**

* **共同作成:**
  マークダウン ファイルをチームメンバーや他人と共同でエディットできるように、.dotm ファイルに変換します。これにより、マイクロソフト オフィス アプリケーション（Word, Excel, PowerPoint, Outlookなど）とのシームレスなインテグレーションが可能になります。

* **自動生成:**
  .dotm ファイルを利用して、レポートやプレゼンテーションなどのドキュメントの自動生成を実現します。これにより、ダイナミックなコンテンツと テンプレートを活用した効率的な作成が可能になります。

* **マイクロソフト オフィス スーツにインテグレーション:**
  マークダウン ファイルを .dotm ファイルに変換し、Word, Excel, PowerPoint, Outlookなど人気のあるマイクロソフト オフィス スートとシームレスに連携できるようにします。

* **サーバー側 レンダリングや静的サイト ジェネレーション:**
  .dotm ファイルをサーバー側でレンダリングし、静的ウェブ サイトのジェネレーション에効率的に使用することが可能になります。これにより、ウェブ開発とデプロイメントが高速で実現できます。

* **バージョン コントロールや変更履歴:**
  マークダウン ファイルを .dotm ファイルに変換し、GitやMercurialなどのバージョン コントロール システムを利用して、ドキュメントの変更履歴や共同作成が可能になります。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}