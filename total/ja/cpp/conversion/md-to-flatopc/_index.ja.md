---
title: MDをFLATOPCにエクスポートするためのC++API
description: C++アプリケーション内でMDをFLATOPCに変換します。

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: FLATOPC
otherformats: MARKDOWN DOTX DOTM MHTML WORDML OTT XAMLFLOW ODT PCL DOCM DOT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="MDをFLATOPCにエクスポートするためのC++API" h2="サードパーティのアプリケーションを必要とせずに、C++アプリケーション内でMDをFLATOPCにレンダリングする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)ファイル形式の自動化ライブラリを使用すると、C++開発者は2つの簡単な手順でMDをFLATOPCに変換できます。まず、[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)APIを使用して、MDファイル形式をDOCに変換できます。次に、高度なWordドキュメント処理API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、DOCをFLATOPCにエクスポートできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MDをFLATOPCにレンダリングするC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してMDファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)メンバー関数を使用してMDをDOCに変換します
3. Aspose.Words APIの[ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用してDOCファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)メンバー関数を使用してドキュメントをFLATOPC形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MD file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.md");
// save MD as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as FlatOpc
wordDoc->Save(u"output.FlatOpc");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してMDドキュメントのパスワードを変更する" %}}
MDをFLATOPCにレンダリングする過程で、パスワードで保護されたMDを開き、そのパスワードを変更することもできます。 MDファイルのパスワードを変更するには、そのドキュメントの所有者パスワードを知っている必要があります。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)でパスワードで保護されたPDFドキュメントをロードするには、所有者のパスワードを指定し、ChangePasswordsメソッドを使用してパスワードを変更します。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介したFLATOPCファイル編集の制限" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、FLATOPCファイルの編集を制限することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。 APIを使用すると、[ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype)列挙パラメーターを使用してコンテンツを制限する方法を制御できます。次のコード例は、フォームフィールドでの編集のみが可能になるように、ドキュメントでの編集を制限する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.FlatOpc");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-markdown/" name="MD に MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-dotx/" name="MD に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-dotm/" name="MD に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-mhtml/" name="MD に MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-wordml/" name="MD に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-ott/" name="MD に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-xamlflow/" name="MD に XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-odt/" name="MD に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-pcl/" name="MD に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-flatopc/" name="MD に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-dot/" name="MD に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/md-to-rtf/" name="MD に RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}