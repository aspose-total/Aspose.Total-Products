---
title: C++ API để chuyển đổi MHTML sang PPT
description: Chuyển đổi MHTML sang PPT qua C++ mà không cần sử dụng Microsoft Word hoặc Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: PPT
otherformats: POTX PPSX PPTM PPS POWERPOINT PPSM SWF OTP POTM XAML ODP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất MHTML sang PPT trong Ứng dụng C++" h2="Chuyển đổi MHTML sang PPT trong Ứng dụng C++ của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có phải là nhà phát triển C++ đang tìm cách thêm để tích hợp tính năng chuyển đổi MHTML sang PPT bên trong các ứng dụng C++ của mình không? Bạn có thể làm điều đó trong hai bước đơn giản. Bạn có thể xuất MHTML sang PPTX bằng cách sử dụng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Thứ hai, bằng cách sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), bạn có thể chuyển đổi PPTX sang PPT. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để xuất MHTML sang PPT" %}}
1. Mở tệp MHTML bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi MHTML sang PPTX bằng cách sử dụng hàm phương pháp [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Tải tài liệu PPTX bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Lưu tài liệu sang định dạng PPT bằng hàm thành viên [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) và đặt `Ppt` là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load MHTML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.mhtml");
// save MHTML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Thay đổi mật khẩu của tài liệu MHTML qua C++" %}}
Trong quá trình kết xuất MHTML sang PPT, bạn có thể mở MHTML được bảo vệ bằng mật khẩu và cũng có thể thay đổi mật khẩu của nó. Để thay đổi mật khẩu của tệp MHTML, bạn phải biết mật khẩu chủ sở hữu của tài liệu đó. Bạn có thể tải tài liệu PDF được bảo vệ bằng mật khẩu bằng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) bằng cách chỉ định mật khẩu chủ sở hữu của nó và sử dụng phương pháp ChangePasswords để thay đổi mật khẩu.
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

{{% blocks/products/pf/feature-page-section  h2="Thêm hình ảnh từ web trong tệp PPT qua C++" %}}
Sau khi chuyển đổi MHTML sang PPT, bạn cũng có thể thêm hình ảnh từ web vào tài liệu đầu ra của mình. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) hỗ trợ các thao tác với hình ảnh ở các định dạng phổ biến sau: JPEG, PNG, BMP, GIF và các định dạng khác. Bạn có thể thêm một hoặc một số hình ảnh trên máy tính của mình vào một trang chiếu trong bản trình bày. Mã mẫu trong C++ này chỉ cho bạn cách thêm hình ảnh vào tệp PPT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPT file
auto pres = System::MakeObject<Presentation>("output.ppt");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-potx/" name="MHTML Đến POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-ppsx/" name="MHTML Đến PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-pptm/" name="MHTML Đến PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-pps/" name="MHTML Đến PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-powerpoint/" name="MHTML Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-ppsm/" name="MHTML Đến PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-swf/" name="MHTML Đến SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-otp/" name="MHTML Đến OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-potm/" name="MHTML Đến POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-xaml/" name="MHTML Đến XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-ppt/" name="MHTML Đến PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/mhtml-to-pot/" name="MHTML Đến POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}