---
title: 通过 C++ 将 EMAIL 导出为 GIF
description: 无需使用 Microsoft Word 或 Outlook 即可将 EMAIL 转换为 GIF 的 C++ API

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: GIF
otherformats: DOT OTT PCL JPEG RTF DOC MD WORDML FLATOPC EPUB DOTM TIFF ODT DOTX PDF XPS DOCM EMF TEXT SVG BMP DOCX PS PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 EMAIL 导出为 GIF 的 C++ API" h2="在 C++ 应用程序中将 EMAIL 转换为 GIF，无需 Microsoft Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 开发人员，希望在您的应用程序中添加电子邮件转换功能吗？使用 [Aspose.Email for C++](https://products.aspose.com/email/cpp/)，您可以将 EMAIL 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API，您可以将 HTML 导出为 GIF。这两个 API 都属于 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 EMAIL 转换为 GIF 的 C++ API" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) 类参考打开 EMAIL 文件
2. 使用 [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) 成员函数将 EMAIL 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法将文档保存为 GIF 格式，并将 Gif 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Gif as save format
doc->Save(u"convertedFile.Gif");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 解析 EMAIL 文件" %}}
您不仅可以将 EMAIL 转换为 GIF，还可以阅读、操作和解析 EMAIL 文档。您可以使用 [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API 的 MapiMessage 类获取电子邮件的主题、地址、正文、收件人信息。例如，您可以使用 get_SenderEmailAddress() 属性检查转换的特定发件人电子邮件。
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

{{% blocks/products/pf/feature-page-section  h2="限制 GIF 文件格式编辑的 C++ API" %}}
在将文档从 EMAIL 导出到 GIF 时，您还可以在应用程序中添加文档保护功能。为您的文档添加保护是一个简单的过程，因为您需要做的就是将保护方法应用于您的文档。您可以将保护类型设置为只读以限制用户编辑文档。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Gif");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}