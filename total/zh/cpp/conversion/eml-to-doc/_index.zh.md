---
title: 通过 C++ 将 EML 导出为 DOC
description: 无需使用 Microsoft Word 或 Outlook 即可将 EML 转换为 DOC 的 C++ API

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOC
otherformats: EMF DOTX EPUB DOT DOCX GIF DOTM PS PDF JPEG ODT WORDML RTF MD OTT PCL SVG XPS TEXT BMP PNG FLATOPC DOCM TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 EML 导出为 DOC 的 C++ API" h2="在 C++ 应用程序中将 EML 转换为 DOC，无需 Microsoft Word 或 Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 开发人员，希望在您的应用程序中添加电子邮件转换功能吗？使用 [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/)，您可以将 EML 文件格式转换为 HTML。之后，通过使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API，您可以将 HTML 导出为 DOC。这两个 API 都属于 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 EML 转换为 DOC 的 C++ API" %}}
1. 使用 [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) 类参考打开 EML 文件
2. 使用 [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) 成员函数将 EML 转换为 HTML
3. 使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类加载 HTML
4. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法将文档保存为 DOC 格式，并将 Doc 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://downloads.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Doc as save format
doc->Save(u"convertedFile.Doc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 解析 EML 文件" %}}
您不仅可以将 EML 转换为 DOC，还可以阅读、操作和解析 EML 文档。您可以使用 [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API 的 MapiMessage 类获取电子邮件的主题、地址、正文、收件人信息。例如，您可以使用 get_SenderEmlAddress() 属性检查转换的特定发件人电子邮件。
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

{{% blocks/products/pf/feature-page-section  h2="限制 DOC 文件格式编辑的 C++ API" %}}
在将文档从 EML 导出到 DOC 时，您还可以在应用程序中添加文档保护功能。为您的文档添加保护是一个简单的过程，因为您需要做的就是将保护方法应用于您的文档。您可以将保护类型设置为只读以限制用户编辑文档。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-emf/" name="EML 至 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-dotx/" name="EML 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-epub/" name="EML 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-dot/" name="EML 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-docx/" name="EML 至 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-gif/" name="EML 至 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-dotm/" name="EML 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-ps/" name="EML 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-pdf/" name="EML 至 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-jpeg/" name="EML 至 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-odt/" name="EML 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-wordml/" name="EML 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-rtf/" name="EML 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-md/" name="EML 至 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-ott/" name="EML 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-pcl/" name="EML 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-svg/" name="EML 至 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-xps/" name="EML 至 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-text/" name="EML 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-doc/" name="EML 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-png/" name="EML 至 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-flatopc/" name="EML 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-docm/" name="EML 至 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/eml-to-tiff/" name="EML 至 TIFF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}