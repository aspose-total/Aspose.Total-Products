---
title: 通过 C++ 将 EMAIL 导出为 IMAGE
description: 无需使用 Microsoft Word 或 Outlook 即可将 EMAIL 转换为 IMAGE 的 C++ API

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML MD OTT FLATOPC PNG DOTX GIF PCL EPUB PDF XPS DOT TEXT DOC DOCM SVG DOTM EMF TIFF BMP ODT JPEG PS DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 EMAIL 导出为 IMAGE 的 C++ API" h2="在 C++ 应用程序中将 EMAIL 转换为 IMAGE，无需 Microsoft Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 开发人员，希望在您的应用程序中添加电子邮件转换功能吗？使用 [Aspose.Email for C++](https://products.aspose.com/email/cpp/)，您可以将 EMAIL 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API，您可以将 HTML 导出为 IMAGE。这两个 API 都属于 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 EMAIL 转换为 IMAGE 的 C++ API" %}}
1. 使用 [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) 类参考打开 EMAIL 文件
2. 使用 [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) 成员函数将 EMAIL 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法将文档保存为 IMAGE 格式，并将 Image 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://downloads.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 解析 EMAIL 文件" %}}
您不仅可以将 EMAIL 转换为 IMAGE，还可以阅读、操作和解析 EMAIL 文档。您可以使用 [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API 的 MapiMessage 类获取电子邮件的主题、地址、正文、收件人信息。例如，您可以使用 get_SenderEmailAddress() 属性检查转换的特定发件人电子邮件。
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

{{% blocks/products/pf/feature-page-section  h2="限制 IMAGE 文件格式编辑的 C++ API" %}}
在将文档从 EMAIL 导出到 IMAGE 时，您还可以在应用程序中添加文档保护功能。为您的文档添加保护是一个简单的过程，因为您需要做的就是将保护方法应用于您的文档。您可以将保护类型设置为只读以限制用户编辑文档。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-wordml/" name="MSG 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-md/" name="MSG 至 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-ott/" name="MSG 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-flatopc/" name="MSG 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-png/" name="MSG 至 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-dotx/" name="MSG 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-gif/" name="MSG 至 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-pcl/" name="MSG 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-epub/" name="MSG 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-pdf/" name="MSG 至 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-xps/" name="MSG 至 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-dot/" name="MSG 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-text/" name="MSG 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-doc/" name="MSG 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-docm/" name="MSG 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-svg/" name="MSG 至 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-dotm/" name="MSG 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-emf/" name="MSG 至 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-tiff/" name="MSG 至 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-image/" name="MSG 至 IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-odt/" name="MSG 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-jpeg/" name="MSG 至 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-ps/" name="MSG 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/msg-to-docx/" name="MSG 至 DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}