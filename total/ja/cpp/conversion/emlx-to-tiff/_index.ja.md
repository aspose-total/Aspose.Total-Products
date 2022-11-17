---
title: C++経由でEMLXをTIFFにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMLXをTIFFに変換するC++API

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: TIFF
otherformats: DOC PS FLATOPC DOTM MD RTF DOT GIF DOCM OTT WORDML DOCX PNG JPEG BMP PDF ODT TEXT PCL EPUB EMF DOTX XPS SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EメールをTIFFにエクスポートするC++API" h2="Microsoft WordやOutlookを必要とせずに、C++アプリケーション内でEMLXをTIFFに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内に電子メール変換機能を追加しようとしているC++開発者ですか？ [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/)を使用すると、EMLXファイル形式をHTMLに変換できます。その後、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、HTMLをTIFFにエクスポートできます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLXをTIFFに変換するC++API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)クラスリファレンスを使用してEMLXファイルを開きます
2. [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)メンバー関数を使用してEMLXをHTMLに変換します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メソッドを使用してドキュメントをTIFF形式で保存し、TiffをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://downloads.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Tiff as save format
doc->Save(u"convertedFile.Tiff");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してEMLXファイルを解析する" %}}
EMLXをTIFFに変換できるだけでなく、EMLXドキュメントを読み取ったり、操作したり、解析したりすることもできます。 [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/)APIのMapiMessageクラスを使用して、電子メールの件名、アドレス、本文、受信者情報を取得できます。たとえば、get_SenderEmlxAddress（)プロパティを使用して、変換用の特定の送信者の電子メールを確認できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="TIFFファイル形式の編集を制限するC++API" %}}
EMLXからTIFFにドキュメントをエクスポートするときに、アプリにドキュメント保護機能を追加することもできます。ドキュメントに保護方法を適用するだけなので、ドキュメントに保護を追加するのは簡単なプロセスです。保護タイプを読み取り専用に設定して、ユーザーによるドキュメントの編集を制限できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Tiff");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-doc/" name="EMLX に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-ps/" name="EMLX に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-flatopc/" name="EMLX に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-dotm/" name="EMLX に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-md/" name="EMLX に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-rtf/" name="EMLX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-dot/" name="EMLX に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-gif/" name="EMLX に GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-docm/" name="EMLX に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-ott/" name="EMLX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-wordml/" name="EMLX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-docx/" name="EMLX に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-png/" name="EMLX に PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-jpeg/" name="EMLX に JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-tiff/" name="EMLX に TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-pdf/" name="EMLX に PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-odt/" name="EMLX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-text/" name="EMLX に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-pcl/" name="EMLX に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-epub/" name="EMLX に EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-emf/" name="EMLX に EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-dotx/" name="EMLX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-xps/" name="EMLX に XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/emlx-to-svg/" name="EMLX に SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}