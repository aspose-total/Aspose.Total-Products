---
title: C++経由でEMAILをDOTXにエクスポートする
description: MicrosoftWordやOutlookを使用せずにEMAILをDOTXに変換するC++API

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOTX
otherformats: OTT SVG PNG DOCX DOCM EMF PS TIFF JPEG MD FLATOPC DOTM ODT DOT BMP PDF EPUB DOC RTF GIF PCL WORDML XPS TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EメールをDOTXにエクスポートするC++API" h2="Microsoft WordやOutlookを必要とせずに、C++アプリケーション内でEMAILをDOTXに変換します" >}}

{{% blocks/products/pf/feature-page-summary %}}
アプリケーション内に電子メール変換機能を追加しようとしているC++開発者ですか？ [Aspose.Email for C++](https://products.aspose.com/email/cpp/)を使用すると、EMAILファイル形式をHTMLに変換できます。その後、[Aspose.Words for C++](https://products.aspose.com/words/cpp/)APIを使用して、HTMLをDOTXにエクスポートできます。どちらのAPIも[Aspose.TotalforC++](https://products.aspose.com/total/cpp/)パッケージに含まれています。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAILをDOTXに変換するC++API" %}}
1. [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)クラスリファレンスを使用してEMAILファイルを開きます
2. [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)メンバー関数を使用してEMAILをHTMLに変換します
3. [ドキュメント](https://reference.aspose.com/words/cpp/class/aspose.words.document)クラスを使用してHTMLをロードします
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)メソッドを使用してドキュメントをDOTX形式で保存し、DotxをSaveFormatとして設定します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
コマンドラインから```nuget install Aspose.Total.Cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.Total.Cpp```を使用してインストールします。

または、[ダウンロード](https://releases.aspose.com/total/cpp)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dotx as save format
doc->Save(u"convertedFile.Dotx");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++を介してEMAILファイルを解析する" %}}
EMAILをDOTXに変換できるだけでなく、EMAILドキュメントを読み取ったり、操作したり、解析したりすることもできます。 [Aspose.Email for C++](https://products.aspose.com/email/cpp/)APIのMapiMessageクラスを使用して、電子メールの件名、アドレス、本文、受信者情報を取得できます。たとえば、get_SenderEmailAddress（)プロパティを使用して、変換用の特定の送信者の電子メールを確認できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmailAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="DOTXファイル形式の編集を制限するC++API" %}}
EMAILからDOTXにドキュメントをエクスポートするときに、アプリにドキュメント保護機能を追加することもできます。ドキュメントに保護方法を適用するだけなので、ドキュメントに保護を追加するのは簡単なプロセスです。保護タイプを読み取り専用に設定して、ユーザーによるドキュメントの編集を制限できます。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dotx");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}