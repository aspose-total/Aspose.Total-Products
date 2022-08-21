---
title: Xuất OFT sang DOT qua C++
description: API C++ để chuyển đổi OFT thành DOT mà không cần sử dụng Microsoft Word hoặc Outlook
url: /vi/cpp/conversion/oft-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOT
otherformats: DOTX BMP GIF DOCM FLATOPC XPS DOCX PS WORDML PNG OTT DOC DOTM PCL JPEG EMF RTF TIFF MD EPUB SVG ODT TEXT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để xuất OFT sang DOT" h2="Chuyển đổi OFT thành DOT trong ứng dụng C++ mà không yêu cầu Microsoft Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn là nhà phát triển C++ đang muốn thêm các tính năng chuyển đổi oft vào bên trong các ứng dụng của mình? Sử dụng [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/), bạn có thể chuyển đổi định dạng tệp OFT sang HTML. Sau đó, bằng cách sử dụng API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất HTML sang DOT. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi OFT thành DOT" %}}
1. Mở tệp OFT bằng cách sử dụng tham chiếu lớp [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Chuyển đổi OFT sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Lưu tài liệu sang định dạng DOT bằng phương pháp [Lưu](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) và đặt Dot làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dot as save format
doc->Save(u"convertedFile.Dot");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp OFT qua C++" %}}
Bạn không chỉ có thể chuyển đổi OFT của mình thành DOT mà còn có thể đọc, thao tác và phân tích cú pháp tài liệu OFT. Bạn có thể lấy thông tin chủ đề, địa chỉ, nội dung, người nhận của oft bằng cách sử dụng lớp MapiMessage của API [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/). Ví dụ: bạn có thể kiểm tra oft người gửi cụ thể cho chuyển đổi bằng cách sử dụng thuộc tính get_SenderOftAddress ().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ để hạn chế chỉnh sửa định dạng tệp DOT" %}}
Bạn cũng có thể thêm các tính năng bảo vệ tài liệu trong ứng dụng của mình trong khi xuất tài liệu từ OFT sang DOT. Thêm bảo vệ cho tài liệu của bạn là một quá trình đơn giản, vì tất cả những gì bạn cần làm là áp dụng phương pháp bảo vệ cho tài liệu của mình. Bạn có thể đặt loại bảo vệ thành ReadOnly để hạn chế người dùng chỉnh sửa tài liệu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dot");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-dotx/" name="OFT Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-dot/" name="OFT Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-gif/" name="OFT Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-docm/" name="OFT Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-flatopc/" name="OFT Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-xps/" name="OFT Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-docx/" name="OFT Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-ps/" name="OFT Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-wordml/" name="OFT Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-png/" name="OFT Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-ott/" name="OFT Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-doc/" name="OFT Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-dotm/" name="OFT Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-pcl/" name="OFT Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-jpeg/" name="OFT Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-emf/" name="OFT Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-rtf/" name="OFT Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-tiff/" name="OFT Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-md/" name="OFT Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-epub/" name="OFT Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-svg/" name="OFT Đến SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-odt/" name="OFT Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-text/" name="OFT Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/oft-to-pdf/" name="OFT Đến PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}