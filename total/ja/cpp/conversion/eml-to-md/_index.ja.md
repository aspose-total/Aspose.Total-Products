---
title: C++経由でEMLをMDにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMLをMDに変換するC++API

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: MD
otherformats: EPUB FLATOPC PNG JPEG DOCM BMP PDF GIF RTF WORDML ODT PCL PS XPS TEXT OTT EMF DOTX DOT SVG DOCX DOTM TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EメールをMDにエクスポートするC++API" h2="Microsoft WordやOutlookを必要とせずに、C++アプリケーション内でEMLをMDに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内に電子メール変換機能を追加しようとしているC++開発者ですか？ [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/)を使用すると、EMLファイル形式をHTMLに変換できます。その後、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、HTMLをMDにエクスポートできます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLをMDに変換するC++API" %}}
1. [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)クラスリファレンスを使用してEMLファイルを開きます
2. [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)メンバー関数を使用してEMLをHTMLに変換します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メソッドを使用してドキュメントをMD形式で保存し、MdをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Md as save format
doc->Save(u"convertedFile.Md");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してEMLファイルを解析する" %}}
EMLをMDに変換できるだけでなく、EMLドキュメントを読み取ったり、操作したり、解析したりすることもできます。 [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/)APIのMapiMessageクラスを使用して、電子メールの件名、アドレス、本文、受信者情報を取得できます。たとえば、get_SenderEmlAddress（)プロパティを使用して、変換用の特定の送信者の電子メールを確認できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="MDファイル形式の編集を制限するC++API" %}}
EMLからMDにドキュメントをエクスポートするときに、アプリにドキュメント保護機能を追加することもできます。ドキュメントに保護方法を適用するだけなので、ドキュメントに保護を追加するのは簡単なプロセスです。保護タイプを読み取り専用に設定して、ユーザーによるドキュメントの編集を制限できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Md");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-epub/" name="EML に EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-flatopc/" name="EML に FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-png/" name="EML に PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-jpeg/" name="EML に JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-docm/" name="EML に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-md/" name="EML に MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-pdf/" name="EML に PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-gif/" name="EML に GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-rtf/" name="EML に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-wordml/" name="EML に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-odt/" name="EML に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-pcl/" name="EML に PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-ps/" name="EML に PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-xps/" name="EML に XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-text/" name="EML に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-ott/" name="EML に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-emf/" name="EML に EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-dotx/" name="EML に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-dot/" name="EML に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-svg/" name="EML に SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-docx/" name="EML に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-dotm/" name="EML に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-tiff/" name="EML に TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/cpp/conversion/eml-to-doc/" name="EML に DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}