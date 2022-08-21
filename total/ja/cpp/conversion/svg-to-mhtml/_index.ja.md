---
title: SVGをMHTMLにエクスポートするためのC++API
description: C++アプリケーション内でSVGをMHTMLに変換します。
url: /ja/cpp/conversion/svg-to-mhtml/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: MHTML
otherformats: DOTM WORDML RTF ODT MARKDOWN DOCM DOTX DOT PCL PS OTT XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="SVGをMHTMLにエクスポートするためのC++API" h2="サードパーティのアプリケーションを必要とせずに、C++アプリケーション内でSVGをMHTMLにレンダリングする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)ファイル形式の自動化ライブラリを使用すると、C++開発者は2つの簡単な手順でSVGをMHTMLに変換できます。まず、[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)APIを使用して、SVGファイル形式をDOCに変換できます。次に、高度なWordドキュメント処理API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)を使用して、DOCをMHTMLにエクスポートできます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SVGをMHTMLにレンダリングするC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してSVGファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)メンバー関数を使用してSVGをDOCに変換します
3. Aspose.Words APIの[ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスリファレンスを使用してDOCファイルをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)メンバー関数を使用してドキュメントをMHTML形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.svg");
// save SVG as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してSVGドキュメントのパスワードを変更する" %}}
SVGをMHTMLにレンダリングする過程で、パスワードで保護されたSVGを開き、そのパスワードを変更することもできます。 SVGファイルのパスワードを変更するには、そのドキュメントの所有者パスワードを知っている必要があります。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)でパスワードで保護されたPDFドキュメントをロードするには、所有者のパスワードを指定し、ChangePasswordsメソッドを使用してパスワードを変更します。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介したMHTMLファイル編集の制限" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、MHTMLファイルの編集を制限することもできます。ドキュメントを編集する機能を制限し、特定のアクションのみを許可する必要がある場合があります。 APIを使用すると、[ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype)列挙パラメーターを使用してコンテンツを制限する方法を制御できます。次のコード例は、フォームフィールドでの編集のみが可能になるように、ドキュメントでの編集を制限する方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Mhtml");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-dotm/" name="SVG に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-wordml/" name="SVG に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-rtf/" name="SVG に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-odt/" name="SVG に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-markdown/" name="SVG に MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-mhtml/" name="SVG に MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-dotx/" name="SVG に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-dot/" name="SVG に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-pcl/" name="SVG に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-ps/" name="SVG に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-ott/" name="SVG に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/svg-to-xamlflow/" name="SVG に XAMLFLOW" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}