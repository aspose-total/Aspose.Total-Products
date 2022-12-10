---
title: C++経由でOFTをWORDMLにエクスポートする
description: MicrosoftWordやOutlookを使用せずにOFTをWORDMLに変換するC++API

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: WORDML
otherformats: FLATOPC DOC SVG JPEG DOCX TEXT DOT PCL PS PDF EPUB DOTX RTF OTT TIFF GIF EMF BMP DOCM PNG ODT DOTM XPS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EメールをWORDMLにエクスポートするC++API" h2="Microsoft WordやOutlookを必要とせずに、C++アプリケーション内でOFTをWORDMLに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内に電子メール変換機能を追加しようとしているC++開発者ですか？ [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/)を使用すると、OFTファイル形式をHTMLに変換できます。その後、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、HTMLをWORDMLにエクスポートできます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OFTをWORDMLに変換するC++API" %}}
1. [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)クラスリファレンスを使用してOFTファイルを開きます
2. [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)メンバー関数を使用してOFTをHTMLに変換します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メソッドを使用してドキュメントをWORDML形式で保存し、WordmlをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing WordML as save format
doc->Save(u"convertedFile.WordML");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してOFTファイルを解析する" %}}
OFTをWORDMLに変換できるだけでなく、OFTドキュメントを読み取ったり、操作したり、解析したりすることもできます。 [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/)APIのMapiMessageクラスを使用して、電子メールの件名、アドレス、本文、受信者情報を取得できます。たとえば、get_SenderOftAddress（)プロパティを使用して、変換用の特定の送信者の電子メールを確認できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="WORDMLファイル形式の編集を制限するC++API" %}}
OFTからWORDMLにドキュメントをエクスポートするときに、アプリにドキュメント保護機能を追加することもできます。ドキュメントに保護方法を適用するだけなので、ドキュメントに保護を追加するのは簡単なプロセスです。保護タイプを読み取り専用に設定して、ユーザーによるドキュメントの編集を制限できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.WordML");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-flatopc/" name="OFT に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-doc/" name="OFT に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-svg/" name="OFT に SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-jpeg/" name="OFT に JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-docx/" name="OFT に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-text/" name="OFT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-dot/" name="OFT に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-pcl/" name="OFT に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-ps/" name="OFT に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-pdf/" name="OFT に PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-epub/" name="OFT に EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-dotx/" name="OFT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-rtf/" name="OFT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-ott/" name="OFT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-tiff/" name="OFT に TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-gif/" name="OFT に GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-emf/" name="OFT に EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-wordml/" name="OFT に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-docm/" name="OFT に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-png/" name="OFT に PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-odt/" name="OFT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-dotm/" name="OFT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-xps/" name="OFT に XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/oft-to-md/" name="OFT に MD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}