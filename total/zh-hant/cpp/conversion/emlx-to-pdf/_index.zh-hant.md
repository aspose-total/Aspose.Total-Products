---
title: 通過 C++ 將 EMLX 導出為 PDF
description: 無需使用 Microsoft Word 或 Outlook 即可將 EMLX 轉換為 PDF 的 C++ API

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PDF
otherformats: TIFF DOCX FLATOPC EPUB DOT RTF EMF DOTX DOTM XPS GIF PNG PS OTT WORDML ODT DOCM BMP MD TEXT PCL SVG DOC JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 EMLX 導出為 PDF 的 C++ API" h2="在 C++ 應用程序中將 EMLX 轉換為 PDF，無需 Microsoft Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 開發人員，希望在您的應用程序中添加電子郵件轉換功能嗎？使用 [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/)，您可以將 EMLX 文件格式轉換為 HTML。之後，通過使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API，您可以將 HTML 導出為 PDF。這兩個 API 都屬於 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 EMLX 轉換為 PDF 的 C++ API" %}}
1. 使用 [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) 類參考打開 EMLX 文件
2. 使用 [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) 成員函數將 EMLX 轉換為 HTML
3. 使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類加載 HTML
4. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法將文檔保存為 PDF 格式，並將 Pdf 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Pdf as save format
doc->Save(u"convertedFile.Pdf");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 解析 EMLX 文件" %}}
您不僅可以將 EMLX 轉換為 PDF，還可以閱讀、操作和解析 EMLX 文檔。您可以使用 [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API 的 MapiMessage 類獲取電子郵件的主題、地址、正文、收件人信息。例如，您可以使用 get_SenderEmlxAddress() 屬性檢查轉換的特定發件人電子郵件。
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

{{% blocks/products/pf/feature-page-section  h2="限制 PDF 文件格式編輯的 C++ API" %}}
在將文檔從 EMLX 導出到 PDF 時，您還可以在應用程序中添加文檔保護功能。為您的文檔添加保護是一個簡單的過程，因為您需要做的就是將保護方法應用於您的文檔。您可以將保護類型設置為只讀以限制用戶編輯文檔。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Pdf");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}