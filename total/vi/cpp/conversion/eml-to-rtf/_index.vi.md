---
title: Xuất EML sang RTF qua C++
description: API C++ để chuyển đổi EML thành RTF mà không cần sử dụng Microsoft Word hoặc Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: RTF
otherformats: FLATOPC PNG SVG DOCM DOCX TEXT XPS PCL DOT DOC TIFF DOTM EPUB PS GIF PDF MD WORDML OTT JPEG DOTX BMP EMF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để xuất EML sang RTF" h2="Chuyển đổi EML thành RTF trong ứng dụng C++ mà không yêu cầu Microsoft Word hoặc Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn là nhà phát triển C++ đang muốn thêm các tính năng chuyển đổi eml vào bên trong các ứng dụng của mình? Sử dụng [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/), bạn có thể chuyển đổi định dạng tệp EML sang HTML. Sau đó, bằng cách sử dụng API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất HTML sang RTF. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi EML thành RTF" %}}
1. Mở tệp EML bằng cách sử dụng tham chiếu lớp [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Chuyển đổi EML sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Tải HTML bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Lưu tài liệu sang định dạng RTF bằng phương pháp [Lưu](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) và đặt Rtf làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Rtf as save format
doc->Save(u"convertedFile.Rtf");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Tệp EML qua C++" %}}
Bạn không chỉ có thể chuyển đổi EML của mình thành RTF mà còn có thể đọc, thao tác và phân tích cú pháp tài liệu EML. Bạn có thể lấy thông tin chủ đề, địa chỉ, nội dung, người nhận của eml bằng cách sử dụng lớp MapiMessage của API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Ví dụ: bạn có thể kiểm tra eml người gửi cụ thể cho chuyển đổi bằng cách sử dụng thuộc tính get_SenderEmlAddress ().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ để hạn chế chỉnh sửa định dạng tệp RTF" %}}
Bạn cũng có thể thêm các tính năng bảo vệ tài liệu trong ứng dụng của mình trong khi xuất tài liệu từ EML sang RTF. Thêm bảo vệ cho tài liệu của bạn là một quá trình đơn giản, vì tất cả những gì bạn cần làm là áp dụng phương pháp bảo vệ cho tài liệu của mình. Bạn có thể đặt loại bảo vệ thành ReadOnly để hạn chế người dùng chỉnh sửa tài liệu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Rtf");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-flatopc/" name="EML Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-png/" name="EML Đến PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-svg/" name="EML Đến SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-docm/" name="EML Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-docx/" name="EML Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-text/" name="EML Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-xps/" name="EML Đến XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-pcl/" name="EML Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-dot/" name="EML Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-doc/" name="EML Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-tiff/" name="EML Đến TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-dotm/" name="EML Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-epub/" name="EML Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-ps/" name="EML Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-gif/" name="EML Đến GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-pdf/" name="EML Đến PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-md/" name="EML Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-wordml/" name="EML Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-ott/" name="EML Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-jpeg/" name="EML Đến JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-dotx/" name="EML Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-rtf/" name="EML Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-emf/" name="EML Đến EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/eml-to-odt/" name="EML Đến ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}