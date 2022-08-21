---
title: XSLFOをPPTMに変換するC++API
description: MicrosoftWordまたはAdobeAcrobatReaderを使用せずにC++を介してXSLFOをPPTMに変換する
url: /ja/cpp/conversion/xslfo-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPTM
otherformats: POTX POT ODP POTM PPT PPSX POWERPOINT SWF XAML PPS OTP PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++アプリケーション内でXSLFOをPPTMにレンダリングする" h2="Microsoft <sup>&reg;</sup> PowerPointを使用せずに、C++アプリケーション内でXSLFOをPPTMに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++アプリケーション内にXSLFOからPPTMへの変換機能を統合するために追加しようとしているC++開発者ですか？あなたは2つの簡単なステップでそれを行うことができます。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用して、XSLFOをPPTXにエクスポートできます。次に、[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用して、PPTXをPPTMに変換できます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XSLFOをPPTMにエクスポートするためのC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してXSLFOファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)メソッド関数を使用してXSLFOをPPTXに変換します
3. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPPTXドキュメントをロードします
4. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してドキュメントをPPTM形式で保存し、「Pptm」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pptm format
prs->Save(u"output.pptm", Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してXSLFOドキュメントのパスワードを変更する" %}}
XSLFOをPPTMにレンダリングする過程で、パスワードで保護されたXSLFOを開き、そのパスワードを変更することもできます。 XSLFOファイルのパスワードを変更するには、そのドキュメントの所有者パスワードを知っている必要があります。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)でパスワードで保護されたPDFドキュメントをロードするには、所有者のパスワードを指定し、ChangePasswordsメソッドを使用してパスワードを変更します。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してPPTMファイルにWebから画像を追加する" %}}
XSLFOをPPTMに変換した後、Webから出力ドキュメントに画像を追加することもできます。 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)は、JPEG、PNG、BMP、GIFなどの一般的な形式の画像での操作をサポートしています。コンピューター上の1つまたは複数の画像をプレゼンテーションのスライドに追加できます。 C++のこのサンプルコードは、PPTMファイルに画像を追加する方法を示しています
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPTM file
auto pres = System::MakeObject<Presentation>("output.pptm");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.pptm", SaveFormat::Pptm);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-potx/" name="XSLFO に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-pot/" name="XSLFO に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-pptm/" name="XSLFO に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-potm/" name="XSLFO に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-ppt/" name="XSLFO に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-ppsx/" name="XSLFO に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-powerpoint/" name="XSLFO に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-swf/" name="XSLFO に SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-xaml/" name="XSLFO に XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-pps/" name="XSLFO に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-otp/" name="XSLFO に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/xslfo-to-ppsm/" name="XSLFO に PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}