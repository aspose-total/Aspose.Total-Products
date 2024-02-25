---
title: API C++ để xuất MHTML sang DOTX
description: Chuyển đổi MHTML sang DOTX trong các ứng dụng C++.

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: DOTX
otherformats: ODT DOTM MARKDOWN DOCM PCL WORDML DOT PS OTT XAMLFLOW RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để xuất MHTML sang DOTX" h2="Kết xuất MHTML thành DOTX trong các ứng dụng C++ mà không yêu cầu bất kỳ ứng dụng bên thứ ba nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
Thư viện tự động hóa định dạng tệp [Aspose.Total for C++](https://products.aspose.com/total/cpp/) cho phép nhà phát triển C++ chuyển đổi MHTML thành DOTX trong hai bước đơn giản. Trước tiên, bạn có thể sử dụng API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) để chuyển đổi định dạng tệp MHTML sang DOC. Thứ hai, bằng cách sử dụng API xử lý tài liệu Word nâng cao [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất DOC sang DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để kết xuất MHTML thành DOTX" %}}
1. Mở tệp MHTML bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi MHTML sang DOC bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Tải tệp DOC bằng cách sử dụng tham chiếu lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) của Aspose. AdWords API
4. Lưu tài liệu sang định dạng DOTX bằng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MHTML file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.mhtml");
// save MHTML as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotx
wordDoc->Save(u"output.Dotx");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Thay đổi mật khẩu của tài liệu MHTML qua C++" %}}
Trong quá trình kết xuất MHTML sang DOTX, bạn có thể mở MHTML được bảo vệ bằng mật khẩu và cũng có thể thay đổi mật khẩu của nó. Để thay đổi mật khẩu của tệp MHTML, bạn phải biết mật khẩu chủ sở hữu của tài liệu đó. Bạn có thể tải tài liệu PDF được bảo vệ bằng mật khẩu bằng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) bằng cách chỉ định mật khẩu chủ sở hữu của nó và sử dụng phương pháp ChangePasswords để thay đổi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing MHTML Document
auto doc = MakeObject<Document>(L"input.mhtml", L"owner");
// change password of MHTML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Hạn chế chỉnh sửa tệp DOTX qua C++" %}}
Bạn cũng có thể hạn chế chỉnh sửa tệp DOTX bằng cách sử dụng API [Aspose. AdWords for C++](https://products.aspose.com/words/cpp/). Đôi khi bạn có thể cần giới hạn khả năng chỉnh sửa tài liệu và chỉ cho phép một số hành động nhất định với nó. API cho phép bạn kiểm soát cách bạn hạn chế nội dung bằng cách sử dụng tham số liệt kê [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). Ví dụ mã sau đây trình bày cách hạn chế chỉnh sửa trong tài liệu để chỉ có thể chỉnh sửa trong các trường biểu mẫu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotx");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}