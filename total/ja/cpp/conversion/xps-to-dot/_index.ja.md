---
title: XPSをDOTにエクスポートするためのC++API
description: C++アプリケーション内でXPSをDOTに変換します。

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: DOT
otherformats: OTT ODT MHTML MARKDOWN DOCM DOTM FLATOPC PCL RTF PS WORDML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XPSをDOTにエクスポートするためのC++API" h2="サードパーティのアプリケーションを必要とせずに、C++アプリケーション内でXPSをDOTにレンダリングする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)ファイル形式の自動化ライブラリを使用すると、C++開発者は2つの簡単な手順でXPSをDOTに変換できます。まず、[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)APIを使用して、XPSファイル形式をDOCに変換できます。次に、高度なWordドキュメント処理API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、DOCをDOTにエクスポートできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPSをDOTにレンダリングするC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してXPSファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)メンバー関数を使用してXPSをDOCに変換します
3. Aspose.Words APIの[ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用してDOCファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)メンバー関数を使用してドキュメントをDOT形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dot
wordDoc->Save(u"output.Dot");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してXPSドキュメントのパスワードを変更する" %}}
XPSをDOTにレンダリングする過程で、パスワードで保護されたXPSを開き、そのパスワードを変更することもできます。 XPSファイルのパスワードを変更するには、そのドキュメントの所有者パスワードを知っている必要があります。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)でパスワードで保護されたPDFドキュメントをロードするには、所有者のパスワードを指定し、ChangePasswordsメソッドを使用してパスワードを変更します。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介したDOTファイル編集の制限" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、DOTファイルの編集を制限することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。 APIを使用すると、[ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype)列挙パラメーターを使用してコンテンツを制限する方法を制御できます。次のコード例は、フォームフィールドでの編集のみが可能になるように、ドキュメントでの編集を制限する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dot");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-ott/" name="XPS に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-odt/" name="XPS に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-mhtml/" name="XPS に MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-markdown/" name="XPS に MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-dot/" name="XPS に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-dotm/" name="XPS に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-flatopc/" name="XPS に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-pcl/" name="XPS に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-rtf/" name="XPS に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-ps/" name="XPS に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-wordml/" name="XPS に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xps-to-dotx/" name="XPS に DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}