---
title: TEXをPOTに変換するC++API
description: MicrosoftWordまたはAdobeAcrobatReaderを使用せずにC++を介してTEXをPOTに変換する

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: POT
otherformats: PPT PPS POTX OTP SWF POTM PPSX PPSM POWERPOINT ODP PPTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++アプリケーション内でTEXをPOTにレンダリングする" h2="Microsoft <sup>&reg;</sup> PowerPointを使用せずに、C++アプリケーション内でTEXをPOTに変換する" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++アプリケーション内にTEXからPOTへの変換機能を統合するために追加しようとしているC++開発者ですか？あなたは2つの簡単なステップでそれを行うことができます。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)を使用して、TEXをPPTXにエクスポートできます。次に、[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)を使用して、PPTXをPOTに変換できます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEXをPOTにエクスポートするためのC++API" %}}
1. [ドキュメント](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)クラスリファレンスを使用してTEXファイルを開きます
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)メソッド関数を使用してTEXをPPTXに変換します
3. [プレゼンテーション](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)クラスリファレンスを使用してPPTXドキュメントをロードします
4. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)メンバー関数を使用してドキュメントをPOT形式で保存し、「Pot」をSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class
auto doc = MakeObject<Document>(u"template.tex");
// save TEX as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pot format
prs->Save(u"output.pot", Aspose::Slides::Export::SaveFormat::Pot);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してTEXドキュメントのパスワードを変更する" %}}
TEXをPOTにレンダリングする過程で、パスワードで保護されたTEXを開き、そのパスワードを変更することもできます。 TEXファイルのパスワードを変更するには、そのドキュメントの所有者パスワードを知っている必要があります。 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)でパスワードで保護されたPDFドキュメントをロードするには、所有者のパスワードを指定し、ChangePasswordsメソッドを使用してパスワードを変更します。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してPOTファイルにWebから画像を追加する" %}}
TEXをPOTに変換した後、Webから出力ドキュメントに画像を追加することもできます。 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)は、JPEG、PNG、BMP、GIFなどの一般的な形式の画像での操作をサポートしています。コンピューター上の1つまたは複数の画像をプレゼンテーションのスライドに追加できます。 C++のこのサンプルコードは、POTファイルに画像を追加する方法を示しています
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POT file
auto pres = System::MakeObject<Presentation>("output.pot");
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
pres->Save(u"updated.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-ppt/" name="TEX に PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-pps/" name="TEX に PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-potx/" name="TEX に POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-otp/" name="TEX に OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-swf/" name="TEX に SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-potm/" name="TEX に POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-ppsx/" name="TEX に PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-ppsm/" name="TEX に PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-powerpoint/" name="TEX に POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-pot/" name="TEX に POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-pptm/" name="TEX に PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/tex-to-xaml/" name="TEX に XAML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}