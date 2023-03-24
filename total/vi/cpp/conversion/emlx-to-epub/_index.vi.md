---
title: Xuất EMLX sang EPUB qua C++
description: API C++ để chuyển đổi EMLX thành EPUB mà không cần sử dụng Microsoft Word hoặc Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: PS DOC PCL GIF FLATOPC JPEG ODT EMF BMP DOTM OTT TEXT MD DOT DOCX SVG RTF PDF WORDML XPS PNG TIFF DOTX DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để xuất EMLX sang EPUB" h2="Chuyển đổi EMLX thành EPUB trong ứng dụng C++ mà không yêu cầu Microsoft Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn là nhà phát triển C++ đang muốn thêm các tính năng chuyển đổi emlx vào bên trong các ứng dụng của mình? Sử dụng [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/), bạn có thể chuyển đổi định dạng tệp EMLX sang HTML. Sau đó, bằng cách sử dụng API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất HTML sang EPUB. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi EMLX thành EPUB" %}}
1. Mở tệp EMLX bằng cách sử dụng tham chiếu lớp [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Chuyển đổi EMLX sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Lưu tài liệu sang định dạng EPUB bằng phương pháp [Lưu](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) và đặt Epub làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Epub as save format
doc->Save(u"convertedFile.Epub");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EMLX qua C++" %}}
Bạn không chỉ có thể chuyển đổi EMLX của mình thành EPUB mà còn có thể đọc, thao tác và phân tích cú pháp tài liệu EMLX. Bạn có thể lấy thông tin chủ đề, địa chỉ, nội dung, người nhận của emlx bằng cách sử dụng lớp MapiMessage của API [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/). Ví dụ: bạn có thể kiểm tra emlx người gửi cụ thể cho chuyển đổi bằng cách sử dụng thuộc tính get_SenderEmlxAddress ().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ để hạn chế chỉnh sửa định dạng tệp EPUB" %}}
Bạn cũng có thể thêm các tính năng bảo vệ tài liệu trong ứng dụng của mình trong khi xuất tài liệu từ EMLX sang EPUB. Thêm bảo vệ cho tài liệu của bạn là một quá trình đơn giản, vì tất cả những gì bạn cần làm là áp dụng phương pháp bảo vệ cho tài liệu của mình. Bạn có thể đặt loại bảo vệ thành ReadOnly để hạn chế người dùng chỉnh sửa tài liệu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Epub");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}