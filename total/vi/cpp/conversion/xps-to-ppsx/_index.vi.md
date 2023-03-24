---
title: C++ API để chuyển đổi XPS sang PPSX
description: Chuyển đổi XPS sang PPSX qua C++ mà không cần sử dụng Microsoft Word hoặc Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPSX
otherformats: PPTM OTP ODP PPSM POTX POWERPOINT SWF PPT POT POTM PPS XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất XPS sang PPSX trong Ứng dụng C++" h2="Chuyển đổi XPS sang PPSX trong Ứng dụng C++ của bạn mà không cần sử dụng Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có phải là nhà phát triển C++ đang tìm cách thêm để tích hợp tính năng chuyển đổi XPS sang PPSX bên trong các ứng dụng C++ của mình không? Bạn có thể làm điều đó trong hai bước đơn giản. Bạn có thể xuất XPS sang PPTX bằng cách sử dụng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Thứ hai, bằng cách sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), bạn có thể chuyển đổi PPTX sang PPSX. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để xuất XPS sang PPSX" %}}
1. Mở tệp XPS bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi XPS sang PPTX bằng cách sử dụng hàm phương pháp [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Tải tài liệu PPTX bằng cách sử dụng tham chiếu lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Lưu tài liệu sang định dạng PPSX bằng hàm thành viên [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) và đặt `Ppsx` là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xps");
// save XPS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Thay đổi mật khẩu của tài liệu XPS qua C++" %}}
Trong quá trình kết xuất XPS sang PPSX, bạn có thể mở XPS được bảo vệ bằng mật khẩu và cũng có thể thay đổi mật khẩu của nó. Để thay đổi mật khẩu của tệp XPS, bạn phải biết mật khẩu chủ sở hữu của tài liệu đó. Bạn có thể tải tài liệu PDF được bảo vệ bằng mật khẩu bằng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) bằng cách chỉ định mật khẩu chủ sở hữu của nó và sử dụng phương pháp ChangePasswords để thay đổi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Thêm hình ảnh từ web trong tệp PPSX qua C++" %}}
Sau khi chuyển đổi XPS sang PPSX, bạn cũng có thể thêm hình ảnh từ web vào tài liệu đầu ra của mình. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) hỗ trợ các thao tác với hình ảnh ở các định dạng phổ biến sau: JPEG, PNG, BMP, GIF và các định dạng khác. Bạn có thể thêm một hoặc một số hình ảnh trên máy tính của mình vào một trang chiếu trong bản trình bày. Mã mẫu trong C++ này chỉ cho bạn cách thêm hình ảnh vào tệp PPSX
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPSX file
auto pres = System::MakeObject<Presentation>("output.ppsx");
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
pres->Save(u"updated.ppsx", SaveFormat::Ppsx);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}