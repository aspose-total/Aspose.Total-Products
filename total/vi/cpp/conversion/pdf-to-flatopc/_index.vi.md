---
title: API C++ để xuất PDF sang FLATOPC
description: Chuyển đổi PDF sang FLATOPC trong các ứng dụng C++.
url: /vi/cpp/conversion/pdf-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: FLATOPC
otherformats: PS XAMLFLOW DOT PCL MHTML WORDML MARKDOWN RTF DOCM ODT DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để xuất PDF sang FLATOPC" h2="Kết xuất PDF thành FLATOPC trong các ứng dụng C++ mà không yêu cầu bất kỳ ứng dụng bên thứ ba nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
Thư viện tự động hóa định dạng tệp [Aspose.Total for C++](https://products.aspose.com/total/cpp/) cho phép nhà phát triển C++ chuyển đổi PDF thành FLATOPC trong hai bước đơn giản. Trước tiên, bạn có thể sử dụng API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) để chuyển đổi định dạng tệp PDF sang DOC. Thứ hai, bằng cách sử dụng API xử lý tài liệu Word nâng cao [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất DOC sang FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để kết xuất PDF thành FLATOPC" %}}
1. Mở tệp PDF bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi PDF sang DOC bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Tải tệp DOC bằng cách sử dụng tham chiếu lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) của Aspose. AdWords API
4. Lưu tài liệu sang định dạng FLATOPC bằng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PDF file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pdf");
// save PDF as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as FlatOpc
wordDoc->Save(u"output.FlatOpc");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Thay đổi mật khẩu của tài liệu PDF qua C++" %}}
Trong quá trình kết xuất PDF sang FLATOPC, bạn có thể mở PDF được bảo vệ bằng mật khẩu và cũng có thể thay đổi mật khẩu của nó. Để thay đổi mật khẩu của tệp PDF, bạn phải biết mật khẩu chủ sở hữu của tài liệu đó. Bạn có thể tải tài liệu PDF được bảo vệ bằng mật khẩu bằng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) bằng cách chỉ định mật khẩu chủ sở hữu của nó và sử dụng phương pháp ChangePasswords để thay đổi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tệp FLATOPC qua C++" %}}
Bạn cũng có thể hạn chế chỉnh sửa tệp FLATOPC bằng cách sử dụng API [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/). Đôi khi bạn có thể cần giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. API cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Ví dụ mã sau đây trình bày cách hạn chế chỉnh sửa trong tài liệu để chỉ có thể chỉnh sửa trong các trường biểu mẫu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.FlatOpc");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-ps/" name="PDF Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-xamlflow/" name="PDF Đến XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-dot/" name="PDF Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-pcl/" name="PDF Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-mhtml/" name="PDF Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-wordml/" name="PDF Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-markdown/" name="PDF Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-rtf/" name="PDF Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-flatopc/" name="PDF Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-odt/" name="PDF Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-dotx/" name="PDF Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/pdf-to-ott/" name="PDF Đến OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}